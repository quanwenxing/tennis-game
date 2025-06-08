# Classic Tennis Game

A classic Pong-style tennis game built with HTML5 Canvas and JavaScript.

## Features

- **Single Player vs AI**: Play against an intelligent computer opponent
- **Smooth Controls**: Use W/S keys or arrow keys to control your paddle
- **Score Tracking**: Keep track of your points and misses
- **Pause Function**: Press spacebar to pause/resume the game
- **Responsive Design**: Clean, centered layout that works on different screen sizes

## How to Play

1. Open `tennis-game.html` in your web browser
2. Use the following controls:
   - **W** or **↑** (Up Arrow): Move paddle up
   - **S** or **↓** (Down Arrow): Move paddle down
   - **Spacebar**: Pause/Resume game
3. Try to hit the ball back to the AI opponent
4. Earn points when the AI misses the ball
5. Track your performance with the score counter

## Game Mechanics

- The left paddle is controlled by the player
- The right paddle is controlled by AI that automatically follows the ball
- The ball bounces off the top and bottom walls
- The ball changes angle slightly based on paddle movement when hit
- Score increases when the AI fails to return the ball
- Miss count increases when the player fails to return the ball

## Technical Details

- Built with vanilla HTML5, CSS3, and JavaScript
- Uses Canvas API for smooth 60fps rendering
- Implements collision detection and physics simulation
- Responsive keyboard input handling

## Browser Compatibility

Works in all modern browsers that support HTML5 Canvas:
- Chrome 4+
- Firefox 4+
- Safari 4+
- Edge 12+
- Opera 10+

## Installation

No installation required! Simply download the HTML file and open it in your web browser.

```bash
# Clone the repository
git clone https://github.com/quanwenxing/tennis-game.git

# Open the game
open tennis-game.html
```

## License

This project is open source and available under the MIT License.