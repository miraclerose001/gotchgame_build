# Gotch'A NFT Mint Platform

A web-based NFT minting platform with integrated game mechanics, featuring collectible creatures organized by elemental types and evolution stages.

## Overview

Gotch'A is a React-based application that combines NFT minting with interactive game features. Users can mint NFTs, connect their wallets, and engage with their collectibles through various game mechanics including combat, healing, feeding, and level progression.

## Features

### NFT Minting
- Mint NFTs from multiple collections
- Elemental-based collections: Air, Earth, Fire, and Water
- Three evolution stages per element (EVO1, EVO2, EVO3)
- Multiple creature types per element and stage

### Game Mechanics
- **Combat System**: Attack mechanics for battles
- **Health Management**: HP tracking and healing capabilities
- **Feeding System**: Feed creatures to maintain or improve stats
- **Level Progression**: Level up system with visual feedback
- **Rewards**: Earn rewards through gameplay

### Wallet Integration
- Connect wallet functionality
- Wallet verification system
- Transaction support for minting and game actions

### User Interface
- Modern, responsive design
- Custom pixel art aesthetic
- Multiple custom fonts (DePixel, PressStart2P, Manrope, Mohave, Nunito, Poppins, SAKURATA, THEBOLDFONT)
- Animated level-up effects
- Interactive card-based NFT display

## Project Structure

```
gotchgame_build/
├── index.html              # Main HTML entry point
├── manifest.json           # PWA manifest configuration
├── asset-manifest.json     # Build asset manifest
├── _redirects              # SPA routing configuration
├── robots.txt             # Search engine directives
├── static/
│   ├── css/               # Compiled CSS files
│   ├── js/                # Compiled JavaScript bundles
│   └── media/             # Optimized media assets
├── fonts/                 # Custom font files
├── imgs/
│   ├── game/              # Game UI assets
│   ├── MINT/              # Minting page assets
│   │   ├── icons/         # Game action icons
│   │   └── NFTS/          # NFT collection images
│   ├── social/            # Social media assets
│   └── wallet-checker/    # Wallet verification assets
└── play/                  # Gameplay screen assets
```

## NFT Collections

### Air Element
- **EVO1**: Aries, Eagle, Lion
- **EVO2**: Aries, Eagle, Lion
- **EVO3**: Aries, Eagle, Lion

### Earth Element
- **EVO1**: Buffalo, Deer, Rhino
- **EVO2**: Buffalo, Deer, Rhino
- **EVO3**: Buffalo, Deer, Rhino

### Fire Element
- **EVO1**: Fox, Phoenix, Snake
- **EVO2**: Fox, Phoenix, Snake
- **EVO3**: Fox, Phoenix, Snake

### Water Element
- **EVO1**: Axolotl, Penguin, Squid
- **EVO2**: Axolotl, Penguin, Squid
- **EVO3**: Axolotl, Penguin, Squid

## Deployment

This is a production build configured for static hosting. The `_redirects` file ensures proper SPA routing for all paths.

### Deployment Requirements
- Static file hosting service (Netlify, Vercel, GitHub Pages, etc.)
- Support for client-side routing
- HTTPS recommended for wallet connections

### Build Information
- Main entry point: `index.html`
- CSS bundle: `static/css/main.109dc59c.css`
- JavaScript bundle: `static/js/main.75a2cd8e.js`
- Code splitting: Multiple chunk files for optimized loading

## Browser Support

- Modern browsers with ES6+ support
- Web3 wallet extensions (MetaMask, WalletConnect, etc.)
- JavaScript enabled

## PWA Configuration

The application includes PWA support with:
- Manifest file for installable app experience
- Custom icons (192x192, 512x512)
- Theme color configuration
- Standalone display mode

## Assets

### Fonts
- DePixel (multiple weights and styles)
- PressStart2P-Regular
- Manrope-Regular
- Mohave (Regular, Bold)
- Nunito-Regular
- Poppins Regular
- SAKURATA
- THEBOLDFONT-FREEVERSION

### Game Icons
- Attack, Block, Feed, Heal
- Health, Rewards, Ultimate
- Level, HP, Star indicators

## Notes

- This is a production build directory
- Source code is not included in this build
- All JavaScript and CSS are minified and optimized
- Asset files are hashed for cache busting

## License

Font licenses are included in the `fonts/dePixel/` directory. Please refer to individual font license files for usage rights.
