## Drunken Monk

## Description

Create a game simulating drunken monk journey from his favorite pub to his monastery. He's traveling through a town square full of people and his moves are not stable, some people don't take it lightly.

### Basic rules

- Whole console screen is the your game set (without scrolling)
- There is a margin of width 1 character around whole set that limits players move.
- In the right top corner is a label "Collisions: [amount of collisions]", where [amount of collisions] is replaced with number of collisions each time player collide with other person, more below
 - Implicit number is 0
- The pub is in the left top corner (position of cursor 1,1)
- The monastery is in the bottom right corner
- Player can collide with people on the town square. Every time this happens a counter is incremented.
 - * Player can collide only four times before the game is over *
- Before the game starts it asks user for difficulty level specifying amount of people in the town square, maximum amount is defined as (number of rows - 1) * (number of columns - 1)
 - Let me have some drink, sir - amount of people between 25-35% of whole screen
 - Alcoholic (professional) - amount of people between 36-50% of whole screen
 - I alcohol therefor I am - amount of people between 55-65% of whole screen
- People are randomly generated and don't move over time
 - Think about where not to generate people so the game is actually winnable
- Arrow keys are used to move the player
- There is a 25% chance player will trip that causes player to move 1 to 3 (randomly generated) more steps in the original direction
- Before each step is made possible collision is calculated
 - Player cannot move over a person and stops before him/her
 - There is 20% chance collided person will push back the player 2-3 steps
 - When player collides with another person increment the number of collisions and update the "Collisions:" label
- Player character is H and is White
- Person character is ß and is Blue
- Top/Bottom margin in character is - and is Brown
- Left/Right margin character is | and is Brown

## Technical details
- Turn off console cursor
- Remember how to place cursor somewhere on the screen
- You can store people in a System.Collections.List to get more familiar with it
- Use infinite loop like do/while(true) and exit the loop with user of break, continue or return
- You will probably need to remember your last steps to be able to go back when the player is pushed by a person

## Focus
- Think this through. Use single purpose functions and combining them.
- If you end up with one giant loop trust me it can be done better.
