## Ludo Board Game v1.0

This project is a simple Ludo board game built with HTML, CSS, and JavaScript. It allows users to play Ludo with up to four players.

### Features

* **HTML:**
    * Structured HTML to create the Ludo board layout.
    * Use of divs for representing various board elements (e.g., players, steps, safe zones).
    * Use of `material-icons` for displaying player tokens.
* **CSS:**
    * Styling of the Ludo board and game elements using CSS.
    * Use of `grid` layout to position elements on the board.
    * Responsive design using media queries for optimal view on various screen sizes.
    * Animation effects using `animate.css` for player highlighting and dice rolls.
* **JavaScript:**
    * Implementation of game logic, including:
        * Dice roll functionality.
        * Movement of player tokens based on dice roll value.
        * Detection of player wins.
        * Collision detection for killing other players' tokens.
        * Sound effects using HTML5 audio elements.
    * Use of event listeners for user interactions.
    * Dynamic manipulation of HTML elements using JavaScript.

### Functionality

1. **Player Setup:**
    * The game begins with a setup screen allowing players to enter their names.
    * Players can choose to play with 2, 3, or 4 players.
    * If a player's name is not entered, their tokens are hidden, and they don't participate.

2. **Dice Roll:**
    * Players take turns rolling the dice by clicking on their respective dice buttons.
    * The dice roll is randomized, generating a number between 1 and 6.
    * The dice roll result is displayed on the screen.
    * A sound effect plays when the dice is rolled.

3. **Token Movement:**
    * If a player's token is in their starting position, they can move it out by rolling a 6.
    * Once a token is out, it moves along the track based on the dice roll value.
    * Tokens can only move to empty spaces.
    * Tokens can move into safe zones, protecting them from being killed.
    * Players can choose which token to move, if they have multiple tokens on the board.

4. **Collision Detection:**
    * If a player lands on a space occupied by an opponent's token, the opponent's token is sent back to their starting position.
    * A sound effect plays when a token is killed.

5. **Win Condition:**
    * A player wins when all four of their tokens reach the home position.
    * A win sound effect plays when a player wins.
    * The game ends when one player wins.

### How to Play

1. Open the `index.html` file in a web browser.
2. Enter the names of the players in the setup screen.
3. Click the "Play" button to start the game.
4. Take turns rolling the dice and moving your tokens.
5. The first player to get all four of their tokens home wins!

### Project Structure

The project is structured as follows:

* `index.html`: Main HTML file containing the game structure.
* `main.css`: CSS file responsible for styling the game.
* `game.js`: JavaScript file containing the game logic and functionality.

### License

This project is licensed under the MIT License. 

### Contributions

Contributions are welcome! Feel free to fork this repository and submit pull requests for bug fixes, feature additions, or improvements.
