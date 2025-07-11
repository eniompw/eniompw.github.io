# Simple Mario Game 🍄

A fun browser-based Mario-style platformer game built with HTML5 Canvas and JavaScript! Jump over pipes, collect points, and enjoy the classic Super Mario Bros. theme music.

## 🎮 Game Features

- **Classic Mario Character**: Features the iconic Mario sprite with smooth animations
- **Infinite Runner Gameplay**: Avoid green pipes while collecting points by reaching the flag
- **Dynamic Difficulty**: More pipes spawn as your score increases
- **Run Mechanic**: Hold the right arrow key for 0.2 seconds to make Mario run faster
- **Authentic Audio**: 
  - Classic Super Mario Bros. theme music
  - Sound effects for scoring and game over
  - Music controls with mute/unmute functionality
- **Smooth Graphics**: 
  - Animated clouds in the background
  - Mario sprite from official Super Mario Run
  - Retro-style pixel graphics

## 🕹️ Controls

| Key | Action |
|-----|--------|
| `←` or `A` | Move left |
| `→` or `D` | Move right (hold for running) |
| `Space` or `W` | Jump |
| `M` | Mute/unmute music |
| `Enter` | Restart game (when game over) |

## 🚀 How to Play

1. **Objective**: Avoid hitting the green pipes and reach the flag to score points
2. **Movement**: Use arrow keys or WASD to control Mario
3. **Jumping**: Press Space or W to jump over obstacles
4. **Running**: Hold the right arrow key to build up speed and run faster
5. **Scoring**: Touch the flag to earn points and reset your position
6. **Game Over**: Touching any pipe ends the game

## 🛠️ Technical Features

- **Pure HTML5/CSS3/JavaScript**: No external frameworks required
- **Canvas Rendering**: Smooth 60fps gameplay using requestAnimationFrame
- **Web Audio API**: Dynamic sound generation for game effects
- **Responsive Design**: Optimized for desktop browsers
- **Asset Loading**: Handles external image and audio resources gracefully

## 📁 Project Structure

```
mariogame/
├── index.html          # Main game file containing all code
└── README.md          # This file
```

## 🎵 Audio Credits

- **Theme Music**: Super Mario Bros. original theme song
- **Sound Effects**: Generated using Web Audio API for scoring and game over

## 🖼️ Visual Assets

- **Mario Sprite**: Official sprite from Super Mario Run
- **Background**: Custom-drawn clouds and environment
- **UI Elements**: Retro-style pixel graphics

## 🌐 Getting Started

1. **Clone or download** this repository
2. **Open** `index.html` in a modern web browser
3. **Click** the "Play Music" button if it appears (browser audio policy)
4. **Start playing** using the keyboard controls!

### Browser Requirements

- Modern web browser with HTML5 Canvas support
- Audio support for background music and sound effects
- JavaScript enabled

## 🎯 Game Mechanics

- **Physics**: Realistic gravity and jump mechanics
- **Collision Detection**: Precise hit detection for pipes and flag
- **Progressive Difficulty**: Pipe count increases with score
- **Speed Mechanics**: Running system with acceleration
- **Score System**: Points awarded for each flag reached

## 🔧 Customization

The game is easily customizable! You can modify:

- **Mario size**: Adjust `mario.w` and `mario.h` values
- **Jump height**: Change `jumpPower` variable
- **Game speed**: Modify pipe `speed` values
- **Difficulty scaling**: Adjust pipe spawn logic
- **Visual styling**: Update CSS and canvas drawing functions

## 🎮 Future Enhancement Ideas

- Power-ups and collectible coins
- Multiple levels with different backgrounds
- High score persistence using localStorage
- Mobile touch controls
- Additional enemy types
- Multiplayer support

## 📝 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

---

**Enjoy the game!** 🎮✨

*Press M to mute/unmute music • Press Enter to restart after game over*
