CALCULATOR PROJECT

This is a simple graphical calculator built using Python's Tkinter library. The calculator performs basic arithmetic operations like addition, subtraction, multiplication, division, and percentage, and it also supports parentheses for order of operations.

Features:

Basic arithmetic operations: Addition, Subtraction, Multiplication, Division.
Parentheses support: To control the order of operations.
Percentage calculation.
Clear and reset: Clear the current entry value.
Result display: Displays the result of the calculation.
Error handling: Displays an error message if there's an invalid expression.

Requirements:

Python 3.x
Tkinter (usually comes pre-installed with Python)

Installation:

Ensure Python 3.x is installed on your system. You can download it from the official Python website.
Tkinter is included with Python by default, but if for some reason it's not installed, you can install it using your package manager:
For Ubuntu:
sudo apt-get install python3-tk
For Windows and macOS, Tkinter should be bundled with Python, so no additional installation is needed.

How to Run:

Clone or download the repository to your local machine.
Open a terminal (or command prompt) and navigate to the directory where the script is saved.
Run the script by executing the following command:
python calculator.py
The calculator window should appear, and you can start performing calculations.

Usage:

Click on the buttons for the digits (0-9) and operators (+, -, *, /).
You can use parentheses () to group expressions.
Use the C button to clear the current input.
Click = to get the result of the expression entered in the input field.
In case of an invalid expression, an error message will be displayed.

Example:

If you enter:
(2 + 3) * 4
The result displayed will be:
20

Code Explanation:

Main Components:
Tkinter GUI:
The Tkinter library is used to create the graphical user interface (GUI). It consists of buttons for digits, operators, and special functions (clear, equals).
An Entry widget is used to display the current equation and result.
Button Functions:
Buttons are created for digits (0-9), operations (+, -, *, /), and special buttons like C (clear) and = (calculate result).
Each button is associated with a command that updates the current entry value or performs a calculation.
Operations:
The show function updates the entry value when a button is clicked.
The clear function resets the entry value to an empty string.
The solve function evaluates the current expression using Python's built-in eval() function.
