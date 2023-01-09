# Snakes_and_Ladder

**Game preparation:**
Before starting the game, each player roll the dice. The player who gets 6 first starts the game.
Each time a player rolls the dice, the new square number of their piece should be displayed.

**Rules for locating snakes and ladders:**
We need to have the location of the snakes and ladders, for this purpose, with using the random library, we consider 4 non-repeating random numbers for the ladders and 6 non-repeating random numbers for the snakes.

For the location of the ladders, it should be such that if the desired ladder is in square a, it should be in the range of 1 < a + 6 < 100 and for the location of snakes, they should not be in square 1.

**Start of the game:**
Players move their pieces from left to right. They start from 1 and follow the numbers on the page. If a player get a 6, he first moves his piece 6 units forward and As a prize, he must roll the dice again and move his piece another time.

**Snakes:**
When a player's piece lands on a snake, it moves back to the current square number divided by two.

**Ladders:**
When a player is placed at the base of a ladder, he moves up six squares...

**Capture:**
If player number one moves forward and lands on another player's piece, player number one can capture it. And if it moves backwards, the second player captures the first player's piece.

A player whose piece is captured cannot return to the game until he gets 6.

**End of the game:**
The player who reaches the highest space of the page (100) is the winner of the game.

To win, the player must get the exact number on the dice to reach the last place. If the number that comes on the dice is too high, the player's piece goes forward by the same number but goes back by the remaining number up to 100.
