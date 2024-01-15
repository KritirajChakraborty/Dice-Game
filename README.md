# Dice Game Project

This project is a simple dice game implemented using HTML, CSS, and JavaScript. The game allows two players to take turns rolling a six-sided die. Players accumulate points with each roll, but rolling a one resets the current score. The first player to reach 100 points wins the game.

## How to Play

1. Each player takes turns rolling a six-sided die by clicking the "Roll Dice" button.
2. Accumulate points by rolling numbers other than one. If a one is rolled, the current player loses their turn, and their current score resets.
3. Click the "Hold" button to add the current score to the player's total score. The turn then passes to the next player.
4. The first player to reach or exceed 100 points wins the game.

## Project Structure

- **HTML:** The structure of the game is defined in the HTML file, including player scores, current scores, buttons, and the dice image.
  
- **CSS:** Styling is applied to create an appealing and responsive user interface. It includes colors, layout adjustments, and transitions.

- **JavaScript:** The game logic is implemented using JavaScript. This includes rolling the dice, updating scores, switching players, and determining the winner.

## Key JavaScript Concepts Used

1. **Event Handling:** The game responds to user interactions such as clicking the "Roll Dice," "Hold," and "New Game" buttons.

2. **Conditional Statements:** Conditional statements are used to check if a dice roll is one and to determine if a player has won.

3. **Functions:** Functions are defined to encapsulate reusable blocks of code, such as initializing the game state, switching players, and rolling the dice.

These key JavaScript concepts help create a dynamic and interactive dice game.
