Name: KARMUKILAN.V
Company: CODTECH IT SOLUTIONS
ID: CT08ESX
Domain: Java Programming
Duration: December 2024 to January 2025
Mentor: N.SANTHOSH

Project Overview: Simple Calculator Application

Objective:
The project implements a graphical user interface (GUI) calculator using Java's Swing library. It allows users to perform basic arithmetic operations, including addition, subtraction, multiplication, and division, with real-time input handling.

Key Features:
Interactive User Interface:

A responsive and intuitive calculator layout with buttons for digits, operators, and special functions.
A text field displays the current input and result.

Basic Arithmetic Operations:

Supports addition (+), subtraction (-), multiplication (*), and division (/).
Handles real numbers, including decimal points.

Error Handling:

Displays an error message for invalid operations such as division by zero.

Reset Functionality:

Users can clear the input and reset the calculator state using the C button.

Real-time Calculation:

Results are updated and displayed immediately upon pressing the = button.
Functional Components

Text Field (JTextField):

Displays the current input or result.
Styled for readability with font settings and right alignment.

Button Panel:

A 4x4 grid layout of calculator buttons:
Digits (0-9)
Decimal point (.)
Arithmetic operators (+, -, *, /)
Equals (=) for calculating results.
Each button is styled with a font for uniformity.

Event Handling:

Uses ActionListener to process button clicks.
Handles different types of input:
Numeric input and decimal points.
Operators and execution commands (=).

Calculation Logic:

Maintains state with:
currentInput (String): Current user input.
currentValue (double): Result of calculations.
currentOperator (char): Last selected arithmetic operator.
Performs arithmetic operations based on the selected operator.
Prevents division by zero by displaying an error message.
How It Works
User Input:

Users enter numbers and operations using the on-screen buttons.
Input is displayed in the text field (resultTextField).
Operation Execution:

On entering an operator, the calculator stores the current value and waits for the next input.
On pressing =, it computes the result based on the stored operator and input values.
Reset Functionality:

The C button clears all inputs and resets the calculator.
Error Handling:

Prevents division by zero, displaying an error message without crashing the program.
Technical Details
Swing Components:

JFrame: Main application window.
JTextField: Displays results and input.
JButton: Interactive calculator buttons.
JPanel: Organizes buttons in a grid layout.
Layout:

BorderLayout for overall structure:
Text field at the top.
Button grid in the center.
Logic Flow:

Maintains state across operations for seamless calculations.
Utilizes control structures (switch-case) for operation selection.


  

  
