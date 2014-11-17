#n-Puzzle10411526

A simple N-Puzzle game for Android. Build for the course App Studio at University of Amsterdam.

## The UI
![Alt text](http://i.imgur.com/p5UJqy8.png)

## List of ingredients
- Gamedata
 - ImageChoice `returns the chosenImageid`
 - LevelChoice `returns the difficultyid`
 - wincheck `Checks if the game is over`
 - savegame `Saves game onPause`
- GameLogic `contains the game`
- Movenumber `numnber of moves`
- BitmapFactory `for image cutting/cropping/resizing`
- Listview `for showing possible images`
- Tableview `for the actual gameboard`

## The database
The saved game will be stored with the _Shared Preference_ method, without using a database. This will contain the following:
- game mode
- chosen image id
- number of moves
- places of tiles