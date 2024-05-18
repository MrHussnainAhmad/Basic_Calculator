# Basic_Calculator
Description:

This Python script implements a basic command-line calculator that prompts the user for input, performs arithmetic operations, and displays the result. The script guides the user through a series of inputs to determine the type of calculation (integer or float), the numbers to be operated on, and the desired arithmetic operation. It also includes error handling for invalid inputs and division by zero.
Features:

    Conversion Type Selection:
        The user is asked whether they want to perform calculations using integers or floating-point numbers.
        The input for this selection is case-insensitive (I or F).

    Input for Numbers:
        Depending on the selected conversion type, the user is prompted to input two numbers.
        If the integer mode is selected, the inputs are converted to integers.
        If the float mode is selected, the inputs are converted to floats.

    Arithmetic Operations:
        The user can select from five arithmetic operations: addition (+), subtraction (-), multiplication (*), division (/), and modulus (%).
        The script performs the selected operation and displays the result.

    Error Handling:
        If the user enters an invalid option for conversion type or arithmetic operation, the script displays an error message.
        The script handles division by zero by displaying an error message and preventing the operation.

    Restart Option:
        If the user enters an invalid conversion type, they are given the option to restart the process.

Detailed Code Explanation:

    Function Definition:
        The entire functionality is encapsulated in a function named new_func().

    Initial Prompts and Conversion Type Selection:
        The script prints a welcome message and prompts the user to select the conversion type (I for integer, F for float).
        The input is converted to lowercase to make the comparison case-insensitive.

    Number Input Based on Conversion Type:
        If the user selects integer conversion, the script prompts for two integers.
        If the user selects float conversion, the script prompts for two floating-point numbers.
        If the user enters an invalid conversion type, they are given the option to restart the process or exit.

    Operation Selection and Execution:
        The script displays a list of arithmetic operations and prompts the user to select one.
        Based on the user's selection, the corresponding operation is performed on the two input numbers.
        If division by zero is attempted, an error message is displayed and the operation is aborted.

    Result Display:
        The result of the selected arithmetic operation is displayed to the user.

    Restart Handling for Invalid Conversion Type:
        If the user enters an invalid conversion type, they can choose to restart the process by entering Y or y.

Summary:

This script provides a simple and interactive way for users to perform basic arithmetic operations using either integer or floating-point numbers. It includes user prompts, error handling, and the ability to restart the process in case of invalid inputs.
