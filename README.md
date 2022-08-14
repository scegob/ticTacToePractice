# week11ticTacToe

https://scegob.github.io/week11ticTacToe/

Being on week 11 which is more than half way done with the Promineo Tech bootcamp we have been working on a lot of projects which ahs been fun.
We get to put everything we have learned together to make more complex projects. This week we were told to make a tic-tac-toe application which combines html, css, bootstrap, dom munipulation/ or jquery.
The steps for this project were 

a.	A heading should say whether it is X’s or O’s turn and change with each move made.
b.	Create a tic-tac-toe grid using your HTML element of choice. When a cell in the grid is clicked, an X or O should appear in that spot depending on whose turn it is.
c.	A button should be available to clear the grid and restart the game.
d.	When a player has won, or the board is full and the game results in a draw, a Bootstrap alert or similar Bootstrap component should appear across the screen announcing the winner.
![Screenshot (254)](https://user-images.githubusercontent.com/38927600/184551736-3f077282-8654-4be5-b933-76b6da4bfc5e.png)
Tic-Tac-Toe Game
![Screenshot (255)](https://user-images.githubusercontent.com/38927600/184551741-86fbb9c6-5ef6-4a4d-9247-92908b5d711e.png)
Winner Message
![Screenshot (256)](https://user-images.githubusercontent.com/38927600/184551800-c2621879-1700-4968-8918-466c00840de6.png)
Mobile View

A piece of code that I am proud of is below because I was having trouble getting it to change the text of the current player and when I started to make a change it started
to give the applications a lot of bugs because I had isPlayerOTurn = to the documentation but once I got rid of the = sign it started to do what I wanted.

function swapTurns() {
    isPlayerOTurn = !isPlayerOTurn
    document.getElementById('text-change').innerHTML = `It is player ${isPlayerOTurn ? "O": "X"}`
}

