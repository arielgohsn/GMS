## Broken code
- Missing wrapper for GameServiceWrapper and ComponentRefresh
- Missing start session in game component
- Missing initial state params e.g. customer and lives
- Spaces in file path of customer images
- An incorrect value in a_hundreds and a_cents
- Lack of submit button handling
- When game is completed, a loading screen is shown instead of game over message

## What I fixed
- *Issues mentioned above
- Added parent container for dollar notes in the tray

## Trade-offs/Assumptions made
- This is a web application for solely large screens
- Removed responsive sizes for dollar notes in the tray because the widths were too wide and would overflow the tray
- I didn't keep to the original aspect ratio of the register image file
- Error alert pops up before game over message is shown
