## Colored matrix

## Description

Ask user for a number of rows and columns. For these numbers create two-dimensional array with specified number of columns and rows of which each cell contains a random number betwen from 0 to 20. 

Display the array matrix in the center of your console application.

On the last line of your console aplication ask user for a number by which you will divide the range 0 to 20 and color the numbers in the already displayed matrix accordingly.

For example when user enters number 5 it will divide the numbers into 4 groups 0 to 4, 5 to 9, 10 to 14 and 15 to 20. The color of each group responds to ConsoleColor enumeration. For example first group will be black, second group will be blue, third group will be cyan and forth group will be dark blue.

If user has not provided the number yet, display the numbers in default color.

Redraw the already displayed array matrix as well as the last line question everytime user enters a new number.

## Technical details

* Understand the enumerations (https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/enumeration-types)
* Arrays (https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/arrays/multidimensional-arrays)
* Use System.ConsoleColor (to change colors)
* Use System.Console.Write and System.Console.SetCursorPosition to set cursor at exact position
* Use System.Random (to generate numbers)



