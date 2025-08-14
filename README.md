Lamumu Brick Breaker
Overview
Lamumu Brick Breaker is a vibrant, colorful browser-based game inspired by classic brick-breaking arcade games. Built using HTML5 Canvas and JavaScript, it features a playful aesthetic with a red, blue, and pink color scheme, power-ups, particle effects, and a unique "Lamumu" character theme. The game includes multiple levels with a symmetric flower-patterned brick layout and supports both mouse/touch and keyboard controls.
Features

Dynamic Gameplay: Break bricks using a paddle and ball, with increasing difficulty across three levels.
Power-Ups: Collect power-ups like largePaddle (increases paddle size) and fastBall (increases ball speed) for enhanced gameplay.
Visual Effects: Includes particle effects for brick destruction, glowing elements, and animated character images.
Responsive Controls: Supports mouse, touch, and keyboard (Arrow Left/Right) input for paddle movement.
Level Progression: Automatically advances to the next level upon clearing all bricks, with a congratulatory message upon completing all levels.
Restart Functionality: A restart button appears on game over to reset the game state.
Custom Assets: Uses custom images for the ball (lamumu.png) and characters (character1.jpg, character2.jpg), with a fallback to simple shapes if images fail to load.

Installation

Clone or Download: Download the project files or clone the repository.
File Structure: Ensure the following files are in the correct directories:
index.html: Main game file.
lamumu_images/lamumu.png: Ball image.
lamumu_images/character1.jpg: Left character image.
lamumu_images/character2.jpg: Right character image.
brick_sound/break.mp3: Sound effect for brick destruction.


Serve the Game: Host the files on a web server (e.g., using http-server or a local development server) or open index.html directly in a browser (note: local file loading may be restricted due to CORS).

How to Play

Objective: Use the paddle to bounce the ball and break all bricks in each level.
Controls:
Mouse/Touch: Move the mouse or swipe to control the paddle's horizontal position.
Keyboard: Use the Left Arrow and Right Arrow keys to move the paddle.


Power-Ups: Catch falling power-ups to gain temporary advantages:
Large Paddle: Increases paddle size for easier ball catching.
Fast Ball: Increases ball speed for faster brick breaking.


Game Over: If the ball falls below the paddle, the game ends, and a "Restart Game" button appears.
Winning: Clear all bricks in a level to advance. Complete all three levels to win the game.

Technical Details

Canvas Size: 900x500 pixels, optimized for 17 brick columns.
Brick Layout: Symmetric flower pattern with 17 columns and 10 rows, using three brick types (Normal, Medium, Hard) with varying hit points.
Styling: Uses Google Fonts (Bubblegum Sans) and a gradient background with red, blue, and pink hues.
Animations: Floating title/subtitle, character image animations, and particle effects for brick hits.
Sound: Includes a brick-breaking sound effect (break.mp3).
Power-Up Mechanics: Power-ups spawn with a 20% chance when a brick is destroyed and last for 5 seconds.

Dependencies

Google Fonts: Bubblegum Sans for stylized text.
No external JavaScript libraries: Pure vanilla JavaScript and HTML5 Canvas.

Known Issues

Image Loading: If images in the lamumu_images folder fail to load, the game falls back to basic shapes for the ball and skips character images.
CORS Restrictions: Running locally (file://) may prevent image and sound loading due to browser security policies. Use a local server for best results.
Mobile Touch: Touch controls are supported but may require fine-tuning for sensitivity on some devices.

Contributing
Contributions are welcome! Please submit issues or pull requests via the repository. Ideas for new power-ups, level designs, or visual enhancements are appreciated.
Credits

Developer: @donutlover8595
Assets: Custom images and sound effects designed for the Lamumu theme.

License
This project is licensed under the MIT License. Feel free to use, modify, and distribute as needed.
