# Clockappincpp
Clock app that displays in 24 hour format and 12 hour format

Description: 
This project is a simple console-based clock program that allows users to interact with and manipulate the current time. It displays the time in both 12-hour and 24-hour formats, and offers various functionalities such as adding hours, minutes, and seconds. The program also validates user inputs for the time to ensure that valid values are provided.

Features:
Displays the current time in both 12-hour (AM/PM) and 24-hour formats.
Allows users to:
Add one hour to the clock.
Add one minute to the clock.
Add one second to the clock.
Validates user inputs for setting the time.
Provides a user-friendly menu for interactions.

Requirements:
C++ compiler 

Instructions:

1.) Run the compiled program
2.) Enter the initial time in 24-hour format (hours, minutes, and seconds).
3.) The program will display the current time in both 12-hour and 24-hour formats and present a menu with the following options:
  1: Add one hour.
  2: Add one minute.
  3: Add one second.
  4: Exit the program.
5.) Select an option from the menu to modify the clock or exit the program.

Functions (found in clock.h file):
twoDigitString(): Converts a number into a two-digit string.
nCharString(): Creates a string of a specified character with a given length.
formatTime24(): Formats the time in 24-hour format.
formatTime12(): Formats the time in 12-hour format.
clearInput(): Clears invalid input from the console.
printMenu(): Prints a formatted menu.
getTime24(): Gets the initial time in 24-hour format from the user.
getMenuChoice(): Gets and validates the user's choice from the menu.
displayClocks(): Displays the time in both 12-hour and 24-hour formats.
setHour(), getHour(): Sets and gets the hour.
setMinute(), getMinute(): Sets and gets the minute.
setSecond(), getSecond(): Sets and gets the second.
addOneHour(), addOneMinute(), addOneSecond(): Adds an hour, minute, or second to the current time.
displayMenu(): Displays the menu.
mainMenu(): Handles the main menu loop.


