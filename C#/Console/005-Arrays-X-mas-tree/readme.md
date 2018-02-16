## X-mas tree

## Description

Display a colorful christmas tree in a console application in ASCII characters.

Ask user for a number how strong the trunk will be. Whatever number user's enter defines how many branches there is. For example when user enters trunk width as 3, the branch size will be 4, meaning four full "/\\" at the bottom branch.

The color of /\ is green, color of * is light green and trunk color is brown.

Then display a tree like this
```	
							    **
							   ****
						            II
							   *II*
							  */II\*
							 */\II/\*
							*//\II/\\*
						       */\/\II/\/\*
							  *IIII*
							 */IIII\*
							*/\IIII/\*
						       *//\IIII/\\*
						      */\/\IIII/\/\*
						     *//\/\IIII/\/\\*
						    */\/\/\IIII/\/\/\*
							  IIIIII
							 *IIIIII*
							*/IIIIII\*
						       */\IIIIII/\*
						      *//\IIIIII/\\*
						     */\/\IIIIII/\/\*
						    *//\/\IIIIII/\/\\*
					           */\/\/\IIIIII/\/\/\*
					          *//\/\/\IIIIII/\/\/\\*
					         */\/\/\/\IIIIII/\/\/\/\*
						          IIIIII
							  IIIIII
							  IIIIII    
							  IIIIII   
							  IIIIII
```						  
## Technical detail
- No special class/method is necessary, you should know already everything you need

## Focus
- Focus on validation of user input, don't let him enter non-sense (both in terms of number parsing and minimum-maximum width). Keep user restrained so you can always display the tree correctly (watchout for maximum current instance of Console width)
- Try to do everything reusable and in functions. If you ended up with one big for/if/for/if cycle redo it so you have simple functions with single purpose and combine them together
