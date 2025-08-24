# CS-401 Software Engineering - Die Game

## Die.java logic
1. Create Die Object Constructor
2. Define Die Object with n-sides
3. define getters 
4. define roll method

## DiceGame.java logic

1. create a single die
2. set up 10 rolls
3. consider the following:
id = count++
int roll = dice[i].roll();

question. each die has a starting value of 1. do you define id as count++ because array count begins at zero, and you would prefer to skip a zero as a die face value?

nope. id counts your dice rolls

4. roll 2 die

5. roll cheating dice

## CheatingDie.Logic
if (cheating die rolls a 1)
  return 99 value to player 

reset the die, but die is initialized at 1 now instead of zero

and that's bazar-type logic
