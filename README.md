# Bowling Game Kata
Create a program, which, given a valid sequence of bowling rolls, produces the total score for the game.

The game consists of 10 frames. In each frame the player has two rolls to knock down 10 pins. The score for the frame is the total number of pins knocked down, plus bonuses for strikes and spares.

## Requirements
Write a class BowlingGame that has two methods:

* `roll(int)` is called each time the player rolls a ball. The argument is the number of pins knocked down;
* `getScore()` returns the total score for that game.

Implement your solution by trying to follow the steps below (try not to read ahead):

### Step 1: return the score for a sequence of valid rolls (without bonus points for strikes and spares)
As an example, consider the following invalid sequence of rolls: 3 - 2 - 8 - 8 (you cannot knock down more than 10 pins in a single frame).

### Step 2: handle a spare with correct bonus
A spare is when the player knocks down all 10 pins in two rolls. The bonus for that frame is the number of pins knocked down by the next roll.

### Step 3: handle a strike with correct bonus
A strike is when the player knocks down all 10 pins on his first roll. The frame is then completed with a single roll. The bonus for that frame is the value of the next two rolls.

### Step 4: return the correct result for a game of 10 frames
In the tenth frame a player who rolls a spare or strike is allowed to roll the extra balls to complete the frame. However no more than three balls can be rolled in tenth frame.

Remember to refactor your code to improve modularity & readability.

## General requirements
- **We would love to see your submission written in JavaScript**. Although, you can use whatever language and frameworks you want. Use something that you know well.
- **Provide a README with instructions** on how to compile and run the application.

**IMPORTANT:**  Implement the requirements focusing on **writing the best code** you can produce.

**CODE SUBMISSION:** Add the code to your own Github account and send us the link.
