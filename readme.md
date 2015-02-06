## Full Ride Code Challenge

### Yahtzee Challenge

**Object**: Roll dice for scoring combinations, and get the highest total score.

**Game Summary**: On each turn, roll the dice up to 3 times to get the highest 
scoring combination for one of the categories on the scorecard.  After you
finish rolling, **you must place a score or a zero in one of the category boxes on
the score card**.  The game ends when a player has filled all the categories.
Scores are totaled and the player with the highest total wins.

**Taking a turn**: On your turn, you may roll the dice up to 3 times, although
you may stop and score after your first or second roll.

Example:  

_First Roll_: You roll all 5 dice and you decide to keep 3 of the rolls.  
_Second Roll_: You roll the other 2 dice and get 1 that you want to keep.  
_Third Roll_: You don't roll what you want so you keep the 4 and fill in a
category on your scorecard.  

**Simplified Scorecard**:  

|Category   |What to score  |
|-----------|---------------|
|Ones       |Total of ones  |
|Twos       |Total of twos  |
|Threes     |Total of threes|
|Fours      |Total of fours |
|Fives      |Total of fives |
|Sixes      |Total of sixes |
|Full House |25 points      |
|YAHTZEE    |50 points      |
|Chance     |Total all dice |


**Yahtzee**: Score in this box only if the dice show five of the same number (5
of a kind).  

**Chance**: Score the total of _any_ 5 dice in this box.  This catch-all
category comes in handy when you can't (or don't want to) score in another
category, and don't want to enter a zero for a category.

**Challenge Guidelines**: In the real game of Yahtzee there are bonus points and
more categories but for this challenge you can ignore that those exist.

#### Minimum Requirements:  
1.  You can play the game with at least 1 player.  
2.  There is some sort of introduction screen that prompts the user to play the game.  
3.  There is a scorecard that keeps track of your score.  
4.  The game must be developed using Ruby, Sinatra, or Rails.  The game can be a
terminal game or on a web page using one of the above frameworks.  You may also
use the Gosu framework (used for building games in Ruby).
5.  Players are not allowed to have a turn that doesn't fill in a category with
a number or zero.  
6.  Players are able to choose which category they want to use for a particular
turn (end of the 3 rolls).  Example: after my 3 rolls lets say I got [1,1,4,1,5] I should be able to choose
whether I want that roll to count for my `Ones` or `Chance`.  
7.  Once a player fills all categories the game ends.  


#### Extended Requirements:
1.  Make the game 1-4 players.  
2.  Make an AI that a single player can play against.  
3.  Allow the AI to have different difficulty settings.  
4.  Keep track of high scores so you can try and get the best score possible.  
