
# JavaScript Calculator 2

This is an interactive calculator project built using HTML, CSS, and JavaScript. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The calculator also handles decimal numbers and displays the result immediately.
## Project Overview

The Calculator 2.0 project features a simple and intuitive calculator interface. Users can input numbers and select operations through buttons, and the result is displayed in a text box.

## Features

- Basic Operations: Addition, subtraction, multiplication, and division.
- Clear Button: The "C" button clears the current input.
- Decimal Point: Users can add decimal points to their inputs.
- Result Display: The result of the calculation is displayed dynamically when the equals button is pressed.
## Tech Stack

**HTML**: For the structure of the calculator interface.
**CSS**: For styling and layout of the calculator, including using Bootstrap for responsive design.
**JavaScript**: To handle the arithmetic calculations, input handling, and dynamic updates of the result.
## Code Explanation

JavaScript Logic

- Handling Button Clicks: When a button is clicked, the JavaScript function calcular() is called.
- Input Management: Depending on whether the button clicked is an operator or a number, the appropriate action is taken. Numbers are added to the current input, and operators are appended to the existing equation.
- Clear Functionality: The "C" button clears the input field.
- Calculating Result: The eval() function is used to evaluate the expression entered in the input field when the "=" button is clicked.
## Folder Structure

- index.html: The main HTML file containing the structure of the calculator.
- calculadora.css: Custom CSS file containing the styles for the calculator layout and buttons.
- script.js: JavaScript file containing the logic for the arithmetic operations and dynamic updates of the result.
## License

This project is for educational purposes and is open to use or modify as needed.
