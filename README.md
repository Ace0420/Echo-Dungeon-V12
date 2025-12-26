# Echo Dungeon V12 - Blind-First Edition

A voice-controlled dungeon crawler RPG designed specifically for blind and visually impaired players.

## Features

- **100% Voice Controlled**: All game interactions happen through voice commands
- **Audio Feedback**: All game state communicated through text-to-speech
- **Three Classes**: Warrior, Mage, and Rogue with unique abilities
- **Deep Progression**: 30+ dungeon levels with scaling enemies and loot
- **Save/Load System**: PIN-based saves using browser localStorage
- **Full-Screen Touch Control**: Tap anywhere to activate voice input

## Quick Start

1. Open `index.html` in Chrome, Edge, or another browser with speech recognition support
2. Tap the screen to begin
3. Say "warrior", "mage", or "rogue" to choose your class
4. Use voice commands to explore, fight, and loot!

## Voice Commands

### Movement
- **North/Forward** - Move north
- **South/Back** - Move south  
- **East/Right** - Move east
- **West/Left** - Move west

### Exploration
- **Look around** - Describe current room
- **Search** - Search room for hidden items
- **Open chest** - Loot treasure chests
- **Drink fountain** - Use healing fountain
- **Merchant** - Talk to merchants
- **Go down stairs** - Descend to next level

### Combat
- **Attack** - Basic attack
- **Defend** - Reduce incoming damage by 50%
- **Special** - Use class ability
- **Cast [spell name]** - Use learned spell
- **Use potion** - Consume a potion
- **Flee** - Attempt to escape

### Equipment
- **Equip [item]** - Equip weapon/armor
- **Wear ring** - Equip a ring (max 10)
- **Equip amulet** - Equip an amulet (max 1)
- **Equip bracelet** - Equip a bracelet (max 2)
- **Remove ring/bracelet** - Unequip accessories

### Information
- **Status** - View character stats
- **Inventory** - List items
- **Help** - Show available commands
- **Hint** - Get contextual hints

### System
- **Save game** - Save with 4-digit PIN
- **Load game** - Load with PIN
- **Readme** - Full instructions
- **License** - Copyright information

## File Structure

```
echo-dungeon/
├── index.html          # Main entry point
├── css/
│   └── styles.css      # Visual styles
├── js/
│   ├── data/           # Game data
│   │   ├── classes.js      # Player classes
│   │   ├── equipment.js    # Weapons & armor
│   │   ├── abilities.js    # Spells & rings
│   │   ├── enemies.js      # Monster definitions
│   │   ├── items.js        # Potions & treasures
│   │   └── rooms.js        # Room types
│   ├── core/           # Core systems
│   │   ├── game-state.js   # Central state
│   │   ├── audio.js        # Text-to-speech
│   │   ├── voice.js        # Voice recognition
│   │   └── save-load.js    # Save/load system
│   ├── systems/        # Game systems
│   │   ├── dungeon.js      # Dungeon generation
│   │   ├── combat.js       # Battle system
│   │   ├── inventory.js    # Item management
│   │   ├── merchant.js     # Trading system
│   │   └── player.js       # Character system
│   ├── commands/       # Command handlers
│   │   ├── movement.js     # Movement commands
│   │   ├── actions.js      # Action commands
│   │   ├── combat-commands.js  # Combat commands
│   │   └── info.js         # Information commands
│   └── main.js         # Initialization
└── README.md           # This file
```

## Browser Requirements

- Chrome 33+ or Edge 79+ (recommended)
- HTTPS connection (required for voice recognition)
- JavaScript enabled
- Speakers or headphones for audio

## License

Copyright 2025 Asa Hartz Games

This game is provided FREE to the community, especially the blind and visually impaired.

**You MAY:**
- Play and share for free
- Modify for personal use
- Use for education
- Create accessibility improvements

**You MAY NOT:**
- Sell or charge for access
- Include in paid products
- Monetize with ads
- Remove this license

Contact: Acejames419@gmail.com
