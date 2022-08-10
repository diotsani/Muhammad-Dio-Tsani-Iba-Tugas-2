# Muhammad-Dio-Tsani-Iba-Tugas-2
flappy_floppy
## Issue 1 - Name _score does not exist - Very High
- Click console to find the name of the wrong content
- Rename _score
## Issue 2 - Tap controller rigidbody hides inherited - Low
- Click console to go to that line
- Add keyword new in the New Rigidbody2D
## Issue 3 - Null reference countdown text
- Click console to go to that line
- Find all reference in the scripts
- Add + on countodown finished in script game manager on enable
## Issue 4 - Game over true
- Check function game over in script game manager
- Change return !gameOver be return gameOver
## Issue 5 - Rigidbody addforce vector2 down
- Check script tap controller input mouse button
- Change rigidbody addforce vector2 down be rigidbody addforce vector2 up
## Issue 6 - Plane not detecting wood
- Check tag in plane & wood
- Change tag in prefab bottom wood from Untagged be DeadZone
- Check script tap controller on trigger enter 2d
- Change col gameobject tag DeadZones be DeadZone
## Issue 7 - Uncountable high scores
- Check script high score text
- Check script game manager which calls the function playerPrefs
- Change if score < saved score be if score > saved score
## Issue 8 - Adjust environment
- Change default spawn pos clouds & stars
