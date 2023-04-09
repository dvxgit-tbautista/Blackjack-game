# Blackjack Game
This is a simple implementation of the popular card game Blackjack using JavaScript.

## How to Play
The goal of Blackjack is to beat the dealer by having a hand value of 21 or as close to 21 as possible without exceeding it.<br><br>

At the start of the game, you will be dealt two cards, and the dealer will also receive two cards. Each card has a value that is either equal to the number on the card or 10 for face cards. An Ace can have a value of either 1 or 11.<br><br>

To get started, click on the "Start Game" button. You will be dealt two cards, and the total sum of their values will be displayed. You can then decide to draw another card or stick with your current hand. If the total sum of your cards exceeds 21, you will lose the game.<br><br>

If you are lucky enough to have a hand value of exactly 21, you will win the game instantly. If the dealer has a hand value of less than 21, the player with the highest hand value wins the game.<br><br>

## Code Structure
The game is implemented in JavaScript, with the main logic located in the index.js file. The getRandomCard function generates a random card from a deck of cards, and the startGame function initiates the game by generating the first two cards for the player. The renderGame function updates the user interface based on the current game state, and the newCard function allows the player to draw a new card.

## How to Run
To run the game, simply open the index.html file in a web browser. The game will automatically start when the page loads, as long as the necessary files are included.
