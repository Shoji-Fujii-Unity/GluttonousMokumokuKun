# Gluttonous Mokumoku-kun

A browser-based action game where you eat dots and move through procedurally generated mazes.
No external libraries or server are required.

## How to Start

Open `index.html` in a web browser.
Portrait orientation is recommended on smartphones.

## Screenshots

### Title Screen

The title screen shows the current best score and best stage, with buttons for EASY, NORMAL, and HARD difficulty levels.

![Title screen](assets/screenshots/title-screen.png)

### Game Screen

The game screen displays the score, stage, remaining lives, maze, dots, ghosts, items, and on-screen controls.
The top-right buttons provide pause, sound, language, D-pad position, and settings controls.

![Gameplay overview](assets/screenshots/gameplay-overview.png)

## How to Play

Choose EASY, NORMAL, or HARD on the title screen.
Eat every dot in the maze to clear the stage.
Touching a ghost costs one life. Eating a power dot lets you defeat ghosts for a limited time.
From stage 2 onward, items may appear that increase speed, provide a shield, or repel ghosts.
A fruit appears after certain conditions are met. Eat it to earn bonus points.

## Controls

- Keyboard: Arrow keys or W/A/S/D
- Smartphone: On-screen D-pad or swiping on the screen
- Pause: `P`, `Esc`, or the pause button at the top of the screen
- Top buttons: Toggle sound, change language, move the D-pad, and open settings

## Settings and Saved Data

You can adjust BGM volume, sound-effect volume, and vibration.
High scores and settings are stored in the browser's `localStorage`.
Clearing the browser's site data also resets these records.

## Supported Languages

Japanese, English, Chinese, Korean, and Spanish are supported.
Press the language button to cycle through them.
