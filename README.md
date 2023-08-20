# Loops-in-CPP

# Code-5

# Title:
To demonstrate the use of 'for' loop.

# Theory:
A for loop is a repetition control structure that allows you to efficiently write a loop that needs to execute a specific number of times.;The syntax of a for loop in C++ is −for ( init; condition; increment ) {  statement(s); }

# Algorithm:
Algorithm includes: 1)Include necessary header files. ;2)Declare num1 as an integer for user input. ;3)Output "Enter a positive number: ". ;4)Read user input into num1. ;5)Use a for loop to iterate from 1 to 10: Output num1 * i = product. ;5)Return 0 to indicate successful program completion.

# Explanation of Code:
**Include Header Files**:Include the <iostream> header for input and output operations.Include the <bitset> header (unused in this code). ;**Namespace Declaration**:Use the using namespace std; declaration to avoid prefixing standard library elements with std::. ;**Main Function**:Define the main function where the program execution starts. ;**Variable Declaration and User Input**: ;Declare an integer variable num1.Output the message "Enter a positive number: ".Read the user input into num1. ;**Multiplication Table Calculation and Display**:Use a for loop to iterate from 1 to 10.
Inside the loop: Output the value of num1 followed by " * " and the current value of i. Calculate the product of num1 * i. Output " = " followed by the product. Move to the next line. ;**End of Main Function**:Return '0' to indicate successful program execution.


**END OF CODE-5**

# Code-6

# Title:
This C++ code prompts the user to input a number and then calculates and displays the multiplication table for that number from 1 to 10 using a 'do-while'.

# Theory:
A '**do-while**' loop is used in C++ (and many other programming languages) when you want to execute a block of code repeatedly as long as a certain condition is met. The primary difference between a '**do-while**' loop and other loop constructs like '**while**' and '**for**' loops is that a '**do-while**' loop guarantees that the loop body will be executed at least once, regardless of whether the condition is initially true or false.

# Algorithm:
Algorithm includes: 1)Include necessary header files. ;2)Declare variables a and i. ;Output "Input a number :" to prompt the user. ;Read user input into a. ;Use a do-while loop to repeatedly output the multiplication table:
Output i X a = i * a.Increment i.Continue looping while i is less than or equal to 10. ;Return 0 to indicate successful program completion.

# Explanation of Code:
**Include Header Files**:Include the <iostream> header for input and output operations. ;**Namespace Declaration**:Use the using namespace std; declaration to avoid prefixing standard library elements with std::. ;**Main Function**:Define the main function where the program execution starts. ;**Variable Declarations and User Input**:Declare an integer variable a.Initialize an integer variable i to 1 for the multiplication factor.Output "Input a number :" to prompt the user.Read user input into a. ;**Do-While Loop for Multiplication Table**:Use a do-while loop to repeatedly calculate and display the multiplication table.Inside the loop:
Output i X a = i * a in the desired format.Increment the value of i.Continue looping while i is less than or equal to 10. ;**End of Main Function**:Return 0 to indicate successful program execution.

**END OF CODE-6**
