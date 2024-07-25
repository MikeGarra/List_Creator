# List_Creator
Number List Creator

Author: Michael Garramone

Part1:

I created a program that allows for a user to choose from a select number of options in a menu. The user may use both lower and upper case lettering of the option they choose. 
If the user has not added any numbers to the list, the list will display a message stating that the list is empty and bring the user back to the menu to choose another option. 
In this section of code labled Part1, it is a very basic level of C++ that shows how the program can be created without the use of functions. 
Though the program is store in the main, it is easy to read showing in the code where each part of the menu's options function. 
I plan to add in a Part2 where the code is cleaned up and functions are added for the process of each option in the menu.

Part 2:

I updated the original List Creator code to have a Switch statement take the place of for loops and nested for loops. Functions were placed in each option of the switch that have the for and nested for loops from the previous code in them. This allows for an easier understanding of what call in the Switch statement is making and what the function is doing for each call made. A function for displaying the menu and displaying the list of numbers was added as well. All that is in the main is the Switch statement, the do...while statement, the entry of the user and the vector of the numbers that will be added by the user when they choose the add_number() funtion.
