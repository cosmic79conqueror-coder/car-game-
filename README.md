# Car Racing Game

A simple yet addictive HTML5 car racing game where you dodge obstacles and collect stars.

## How to Play

1. **Open the game**: Open `index.html` in any web browser (Chrome, Firefox, Edge, Safari)

2. **Start the game**: Click the "Start Game" button on the startup screen

3. **Select Difficulty**: Choose from three difficulty levels:
   - **Easy**: Slower obstacles, slower stars, less frequent spawns
   - **Medium**: Moderate speed and spawn rate (default)
   - **Hard**: Fast obstacles, fast stars, frequent spawns

4. **Control the car**: Use the **Arrow Keys** on your keyboard:
   - **Left Arrow**: Move car left
   - **Right Arrow**: Move car right
   - The car stays within the road lanes automatically

5. **Gameplay objectives**:
   - **Avoid red obstacles** - Collision ends the game
   - **Collect yellow stars** - Worth 50 points each
   - **Score increases** as you survive longer
   - **Game speeds up** every 50 points

6. **Pause/Resume**: Press **Esc** key during gameplay to pause/resume
   - Click "Resume" to continue
   - Click "Exit" to return to the start screen

7. **High Score**: Your highest score is saved to your browser's localStorage
   - Displayed on the top right of the screen
   - Persists even after you close the browser

## Controls Summary

| Action | Control |
|--------|---------|
| Move Left | ← Arrow Key |
| Move Right | → Arrow Key |
| Pause/Resume | Esc Key |
| Start Game | Click "Start" button or Press Enter |

## Game Features

- ✅ Three difficulty levels (Easy, Medium, Hard)
- ✅ Automatic road lane constraints keep car in bounds
- ✅ Progressive speed increase as score rises
- ✅ Star collection for bonus points
- ✅ High score persistence
- ✅ Pause menu with Resume/Exit options
- ✅ Responsive design works on mobile and desktop
- ✅ Moving road lines create motion illusion

## Technical Details

- Built with HTML5 Canvas
- No external dependencies required
- Lightweight and runs in any modern browser
- Score and high score saved to localStorage
- Game loop runs at 60fps using requestAnimationFrame

## File Structure

```
Car racing/
│
├── index.html    # Main game file (HTML, CSS, JavaScript)
└── README.md     # This file - game instructions and features
```

## Enjoy the Game!

Test your reflexes, beat your high score, and see how long you can survive on the highway!