# Exercise Files and Errors

Create a Java program that manages files by performing various operations such as creating, showing, editing, and deleting files. Utilize the concept of exceptions to handle errors gracefully.
The program should utilize the Scanner class to read user input.
The program should present a menu to the user with the following options:
- Create a new file (Mode 1)
- Show the content of an existing file (Mode 2)
- Edit an existing file by adding a new line of text (Mode 3)
- Delete an existing file (Mode 4)
- Exit the program (Mode 5)


> Implement appropriate exception handling throughout the program to handle cases such as file not found, file already exists, input validation, etc.
> ! Test your program
> Test the program with different inputs to observe how exceptions are handled and to ensure the program behaves as expected in various scenarios.

## Task 1 - Create file
If the user chooses Mode 1, prompt the user to enter a file name and create a new file with that name. Handle the case where the file already exists gracefully by informing the user and asking for a different file name.

## Task 2 - Show file
If the user chooses Mode 2, prompt the user to enter the name of the file they want to view. Display the content of the file if it exists. If the file does not exist, handle the exception by informing the user and returning to the menu.

## Task 3 - Add Text
If the user chooses Mode 3, prompt the user to enter the name of the file they want to edit. If the file exists, prompt the user to enter a new line of text to add to the file. If the file does not exist, handle the exception by informing the user and returning to the menu.

## Task 4 - Delete File
If the user chooses Mode 4, prompt the user to enter the name of the file they want to delete. If the file exists, delete it. If the file does not exist, handle the exception by informing the user and returning to the menu.
