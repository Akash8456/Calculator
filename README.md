Command-Line Calculator – README Objective A simple Python-based Command-Line Calculator that performs basic arithmetic operations: Addition, Subtraction, Multiplication, and **Divis calculator Description

This command-line calculator takes user input via the terminal, allows them to choose an operation, and displays the result.

The program: Prompts the user to choose an operation (1 to 4) Asks for two numeric inputs Performs the selected operation Handles errors like invalid input or division by zero

Features

Addition, Subtraction, Multiplication, Division Handles invalid menu choices Checks for non-numeric input Avoids division by zero

How to Run:

Clone or download the project 2. Open the terminal in the project folder 3. Run the program using:

bash python calculator.py

Code Explanation

add(x, y)Returns the sum ofxandy`.

subtract(x, y)Returns the result ofx - y`.

multiply(x, y)Returns the result ofx * y`.

divide(x, y) Checks if y == 0 to prevent division by zero. Otherwise returns x / y.

main() Displays menu Takes user input Calls appropriate function based on the choice Handles: Invalid operation choices Non-numeric input Division by zero if __name__ == "__main__": Ensures that the script runs only when executed directly, not when imported.

Example Output:

Command-Line Calculator Choose an operation:

Add
Subtract
Multiply
Divide Enter choice (1/2/3/4): 1 Enter first number: 10 Enter second number: 5 Result: 15.0
Requirements: Python 3.x Terminal or Command Prompt

📄 License

This project is open-source and free to use under the MIT License.
