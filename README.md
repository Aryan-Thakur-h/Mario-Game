Watch live - https://mariogameltd.netlify.app/
# Super Mario HTML5

A browser-based Super Mario Bros. clone written in HTML5, JavaScript, and CSS.

## Overview

This is a complete recreation of the classic Super Mario Bros. game mechanics using web technologies. The game features multiple levels, enemies, power-ups, and all the classic platforming action.

## Author

**Original Developer:** Florian Rappl (2012)  
Website: [florian-rappl.de](http://florian-rappl.de)  
Email: mail@florian-rappl.de

**Level Design:**  
Martin Buchner & Patrick Saar

## Technologies Used

- HTML5
- JavaScript (ES5)
- jQuery 1.7.2
- CSS3

## How to Play

Simply open `index.html` in a modern web browser.

### Controls

| Key | Action |
|-----|--------|
| **← / →** | Move left/right |
| **↑** or **Spacebar** | Jump |
| **↓** | Crouch / Slide down pipes |
| **Ctrl** or **A** | Run faster |
| **Ctrl** + **↑** (when Fire Mario) | Shoot fireballs |

### Game Mechanics

- **Small Mario**: Default state, vulnerable to one hit
- **Big Mario**: Obtained by collecting a Mushroom, can break brick blocks
- **Fire Mario**: Obtained by collecting a Fire Flower, can shoot fireballs
- **Invincible Mario**: Obtained by collecting a Star, immune to damage

### Collectibles

- **Mushroom**: Makes Mario Big
- **Fire Flower**: Makes Mario Fire (can shoot)
- **Star**: Grants invincibility
- **Coin**: Collect 100 coins to gain an extra life

### Enemies

- **Goomba (Ballmonster)**: Basic enemy, walks back and forth
- **Green Turtle**: Can be stomped or kicked
- **Spiked Turtle**: Cannot be kicked, avoid from any direction
- **Pipe Plant**: Emerges from pipes at certain intervals

## Project Structure

```
Game/
├── index.html              # Main game entry point
├── README.md               # This file
├── Content/
│   ├── style.css          # Game styling
│   ├── mario-sprites.png  # Mario sprites
│   ├── mario-enemies.png  # Enemy sprites
│   ├── mario-objects.png  # Object/block sprites
│   ├── mario-peach.png    # Princess sprite
│   ├── backgrounds/       # Level backgrounds (01-08)
│   └── audio/             # Sound effects (if available)
└── Scripts/
    ├── main.js            # Core game logic
    ├── constants.js       # Game constants & configurations
    ├── keys.js            # Keyboard input handling
    ├── oop.js             # OOP utilities (Class.extend)
    └── testlevels.js     # Level data (11 levels)
```

## Game Features

- ✅ Multiple levels (11+ complete levels)
- ✅ Parallax scrolling backgrounds
- ✅ Power-up system (Mushroom, Fire Flower, Star)
- ✅ Multiple enemy types with unique behaviors
- ✅ Coin collection and lives system
- ✅ Level progression with save states
- ✅ Sprite-based animations
- ✅ Sound effects support
- ✅ Responsive controls

## Levels

The game includes 11+ levels with increasing difficulty:
1. Level 1-1 (Tutorial)
2. Level 1-2
3. Level 1-3
4. Level 1-4 (Underground)
5. Level 2-1 (Water/Stone themed)
6. Level 2-2
7. Level 3-1
8. Level 3-2
9. Level 4-1
10. Level 4-2
11. Level 5-1 (Final Castle)

## Browser Compatibility

- Chrome/Chromium
- Firefox
- Safari
- Edge

Requires JavaScript and jQuery to be enabled.

## License

This is a fan-made clone for educational purposes. Super Mario is a trademark of Nintendo. Please don't distribute the game or its assets.

## Acknowledgments

- Florian Rappl for the original implementation
- Martin Buchner & Patrick Saar for level design
- Nintendo for the original Super Mario Bros.
