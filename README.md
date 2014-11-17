#n-Puzzle10411526

A simple N-Puzzle game for Android. Build for the course App Studio at University of Amsterdam.

## The UI
![Alt text](http://i.imgur.com/p5UJqy8.png)

## List of classes and mehods
- Gamedata `contains all the relevant game data`
 - imageChoice `returns the chosenImageid`
 - levelChoice `returns the difficultyid`
 - saveGame `saves game onPause`
 - moveNumber `returns the numnber of moves`
- GameLogic `contains the game`
 - scramble `scramble the gameboard after showing it for 3 seconds`
 - checkValidMove `returns a boolean`
 - moveTile `if previous is true then return the board with the moved tile and count 1 to numberMoves`
 - wincheck `checks if the game is over`
- ResetGame ``

## List of APIs
- BitmapFactory `for image cutting/cropping/resizing`
- SharedPreferences `for saving the game data`


## The database
The saved game will be stored with the _Shared Preference_ method, without using a database. This will contain the following:
- game mode
- chosen image id
- number of moves
- places of tiles