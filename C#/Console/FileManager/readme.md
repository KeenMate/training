# C# training

# **File Creator**

## Description

This program will be creating folders containing txt files with their own paths.

## Technical details

* Program will ask you to enter the path.
* Program will ask how many folders you want to make.
* Program will ask how many files will be created in folders.
* Program will use classes System.IO.File, System.IO.Directory, System.IO.StreamWriter
* Try to use "using" statement to ensure all program resources are cleaned

Program will generate entered count of folders in the path. Folders will be called from A to entered count.
In every folder will be created entered count of txt files. Every txt file will contain its own path.
Txt files will be called like this ("000.txt","001.txt","002.txt" etc.)




# **Basic File Operations**

## Description

This program contains working menu.
    Menu helps you to work with files.

Make program that will generate a menu.
Menu contains
1. Show the files in directory
    *   Show summary list (file name, extension, size and create date)  
    *   Show full paths only (file full paths)
2. Delete all files in directory
    *   Confirm before delete (display how many files will be removed)
    *   Display confirmation of each file deleted
3. Create new directory 
    *   Ask user to create directory
        *   Check if the path is valid
        *   Give user max 3 attempts
    *   Maximum length of dir name is 20 characters 
    
## Technical details

*   Program will use classes  System.IO.DirectoryInfo, System.IO.Directory, System.IO.FileInfo
*   Try to divide your code to as many functions as possible so each function does only 1 thing and they combine more complex structures

