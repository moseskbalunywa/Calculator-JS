# Calculator Project

This project is a simple **calculator** built using **HTML**, **CSS**, and **JavaScript**. The calculator performs basic arithmetic operations and is styled to be both functional and visually appealing.

## Features

- **Basic arithmetic**: Addition, subtraction, multiplication, and division.
- **Additional operations**: Modulus (remainder), exponentiation (power).
- **Clear input**: Reset the input fields and results.
- **Decimal input**: Allows decimal point inputs.
- **Responsive layout**: Adjusts well to different screen sizes.

## How to Use

1. **Enter two numbers**: Use the input fields to enter your numbers.
2. **Choose an operator**: Click one of the operator buttons (`+`, `-`, `*`, `/`, `%`, `^`).
3. **Get the result**: Click the `=` button to display the result in the result bar.
4. **Clear the inputs**: Press `C` to reset the calculator.

## File Structure

- `index.html`: The main structure of the calculator.
- `style.css`: Contains the CSS for styling the calculator (written inline in this project).
- `script.js`: The JavaScript file for calculator logic (also inline in this project).

## Code Explanation

### HTML Structure

- The calculator has two input fields (`input1`, `input2`) where users can input numbers.
- There is a result bar that shows the calculated result.
- Operator buttons (`+`, `-`, `*`, `/`, `%`, `^`) trigger their respective operations.
- There are also `C`, `.` (decimal), and `=` buttons to clear, add decimal points, and calculate, respectively.

### JavaScript Functions

1. **Operations**:
   - `telOp()`: Adds two numbers.
   - `trekAf()`: Subtracts the second number from the first.
   - `vermenigvuldig()`: Multiplies two numbers.
   - `deel()`: Divides the first number by the second.
   - `berekenRest()`: Finds the remainder of division.
   - `berekenMacht()`: Raises the first number to the power of the second.

2. **Functionality**:
   - `setOperator()`: Stores the operator selected by the user.
   - `calculate()`: Performs the chosen operation and displays the result.
   - `clearInput()`: Clears the input fields and resets the result.
   - `addDecimal()`: Adds a decimal point to the selected input field.

### CSS Styling

- Buttons have a clean, modern look with hover effects for better user interaction.
- The result display adapts to different content lengths to ensure readability.
- Responsive design ensures the calculator works on various screen sizes.

## Installation

You can easily run this calculator by downloading the files and opening the `index.html` file in your browser.

1. **Clone the repository**:
   ```bash
   git clone https://github.com/moseskbalunywa/Calculator-JS.git
   ```
2. **Open the HTML file**:
   - Navigate to the folder where the files are stored.
   - Open `index.html` in any web browser.

## Contributions
