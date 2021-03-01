# HOG-Game

In Hog, two players alternate turns trying to be the first to end a turn with at least 100 total points. On each turn, the current player chooses some number of dice to roll, up to 10. That player's score for the turn is the sum of the dice outcomes.

Rules
To spice up the game, we will play with some special rules:

### Pig Out. 
##### If any of the dice outcomes is a 1, the current player's score for the turn is 1.
Example 1: The current player rolls 7 dice, 5 of which are 1's. They score 1 point for the turn.
Example 2: The current player rolls 4 dice, all of which are 3's. Since Pig Out did not occur, they score 12 points for the turn.


### Free Bacon. 
##### A player who chooses to roll zero dice scores one more than the minimum of of the ones and tens digit of the opponent's score

Example 1: The opponent has 10 points, and the current player chooses to roll zero dice. The minimum of 0 and 1 is 0, so the current player gains 1 point
Example 2: The opponent has 39 points, and the current player chooses to roll zero dice. The minimum of 3 and 9 is 3, so the current player gains 4 points

### Swine Swap. 
##### After points for the turn are added to the current player's score, if the current and other player's scores share any digits in the same place value, the scores are swapped.
Example 1: The current player has a total score of 41 and the opponent has 83. The current player rolls one dice with value 2. The player's new score is 43, and the opponent's score is 83. The players' scores both have a 3 in the one's place, so the scores are swapped.
Example 2: The current player has a total score of 41 and the opponent has 52. The current player rolls two dice with total value 10. The player's new score is 51, and the opponent's score is 52. The players' scores both have a 5 in the ten's place, so the scores are swapped.

