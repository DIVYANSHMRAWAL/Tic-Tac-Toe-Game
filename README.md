<h1>Tic-Tac-Toe Game in Java</h1>

<h2>Overview:</h2>
<p>This project is a simple, console-based Tic-Tac-Toe game developed using Java. The game allows a human player to play against an AI opponent. The board is represented as a 3x3 grid, and the game includes features such as marking cells, checking for wins, and handling draws. The AI makes moves using a random algorithm, providing a basic challenge to the human player.</p>

<h2>Key Features:</h2>

<h3>Board Initialization:</h3>
<ul>
  <li>A 3x3 character array is used to represent the game board.</li>
  <li>It is initialized to an empty state (' ') in each cell at the start of every game.</li>
</ul>

<h3>Player Types:</h3>

<h4>Human Player:</h4>
<ul>
  <li>Takes user input for row and column choices to place their mark ('X').</li>
  <li>Ensures valid moves, i.e., no overwriting of already filled cells.</li>
</ul>

<h4>AI Player:</h4>
<ul>
  <li>Uses the Random class to place its moves ('O') at random positions on the board.</li>
  <li>The AI simulates a basic level of difficulty by choosing an available space randomly.</li>
</ul>

<h3>Game Logic:</h3>

<h4>Win Conditions:</h4>
<ul>
  <li>The game checks for three consecutive marks in rows, columns, or diagonals after each move.</li>
</ul>

<h4>Draw Condition:</h4>
<ul>
  <li>The game checks if all cells are filled and no winner has been declared, resulting in a draw.</li>
</ul>

<h4>Turn-based System:</h4>
<ul>
  <li>The game alternates turns between the Human Player and AI Player, allowing each to place their respective marks on the board.</li>
</ul>

<h3>Input Validation:</h3>
<ul>
  <li>The game ensures that user input is valid, ensuring that players cannot place their marks on already occupied cells.</li>
</ul>

<h2>Technologies:</h2>

<h3>Java:</h3>
<ul>
  <li>Core Java libraries and classes are used, including basic data structures and random number generation.</li>
</ul>

<h3>Object-Oriented Programming (OOP):</h3>
<ul>
  <li>Key OOP concepts such as Encapsulation, Inheritance, and Polymorphism are applied. The Player class is abstract, with specific implementations for both HumanPlayer and AIPlayer.</li>
</ul>

<h3>Random Number Generation:</h3>
<ul>
  <li>The AI uses the Random class to decide its next move, providing an element of unpredictability to the gameplay.</li>
</ul>

<h2>How to Play:</h2>
<ol>
  <li>Start the game by running the <code>Tic_Tac_Toe</code> class.</li>
  <li>The Human Player is prompted to enter row and column numbers (between 0 and 2) to place their mark ('X').</li>
  <li>The AI Player will randomly choose a valid cell to place its mark ('O').</li>
  <li>The game continues until a win condition is met, or a draw occurs.</li>
  <li>At the end of the game, a message will display the outcome: either the winner or a draw.</li>
</ol>

<h2>How to Run:</h2>
<ol>
  <li>Clone this repository to your local machine.</li>
  <li>Open the project in your favorite Java IDE or text editor.</li>
  <li>Compile and run the <code>Tic_Tac_Toe.java</code> file to start the game.</li>
</ol>

<h2>Screenshots:</h2>
<img src="https://raw.githubusercontent.com/Munanga/Tic-Tac-Toe/master/board.JPG" alt="Tic-Tac-Toe Game Board" width="600" />

