# Guess the number

## Description

The program will general random number that you must guess. The program also calculate how many attempts did it take for you to guess the number.

## Technical details

* Program will load minimum and maximum number from which the random number will be generated from Application Configuration file (https://msdn.microsoft.com/cs-cz/library/ms184658.aspx)
* use Random class to generate the number
* validate user's input (only integer numbers are allowed)
* when the difference between user's number and to be guessed number 
 * is more then 20 (in absolute value) display a little bit more/less 
 * is more then 40 (in absolute value) display far more/less
* after the user guessed the number display statistics 
