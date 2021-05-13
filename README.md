# TicTacToe
This project was built using HTML, CSS, and JavaScript to create a functioning Tic Tac Toe game against the computer. 

## HTML
The HTML build is a basic grid layout using tables and containers to specify the classic 9 space options for the game

## CSS
The CSS sets the grid to be the size desired for the board, removes the outter border, and uses z-indicies to allow images of the X's and O's to be placed respectively on the board. 

## JavaScript 
The JavaScript portion is what makes the game function. First the user has to choose a square to determine the game has started and log what move they made. Each move is logged to an array so the computer can only choose available squares. If the user chooses X then the png file of an X will show in their selected squares and O for the computer. The computer chooses its square based off what is left on the grid and checks possible win conditions. There is a disable click function that stops the user from choosing for the computer and vise versa. After each selection the game checks for a winning condition and if there is a winner, the draw line function is called. The game from there can be cleared and reset for a replay.

