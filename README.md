
# Java Swing Calculator

This project is a simple desktop calculator application built using the Java Swing library. It can perform basic arithmetic operations (addition, subtraction, multiplication, division, modulo).

## ✨ Features

* **Basic Arithmetic Operations:**
    * Addition (+)
    * Subtraction (-)
    * Multiplication (x)
    * Division (/)
    * Modulo (%)
* **Additional Functions:**
    * **C (Clear):** Clears all input and the current result.
    * **DEL (Delete):** Deletes the last entered character.
    * **+/- (Sign Change):** Toggles the sign of the displayed number.
    * **. (Decimal Point):** Allows for decimal number input.
* **User Interface:**
    * A display screen for showing numbers and results.
    * Clickable buttons for numbers, operators, and functions.
* **Error Handling:**
    * Division by zero error.
    * Invalid input format error.

## 📸 Screenshot

<img width="242" alt="image" src="https://github.com/user-attachments/assets/fba7ef75-6ce5-4208-8e85-a30336a40c4f" />

## 🏗️ Code Structure

* **`Calculator.java`**: The main class of the application.
    * **`Calculator()` (Constructor):** Sets the initial state of the calculator and initializes the user interface.
    * **`initUI()`**: Creates and arranges Swing components (JFrame, JLabel, JPanel, JButton) and adds event listeners.
    * **`ButtonClickListener` (Inner Class):** Manages button click events.
    * **`handleNumberInput(String number)`**: Processes input when number buttons are pressed.
    * **`handleDecimalInput()`**: Processes input when the decimal point (.) button is pressed.
    * **`handleOperatorInput(String operator)`**: Processes input when arithmetic operator (+, -, x, /, %) buttons are pressed.
    * **`handleEqualsInput()`**: Performs the calculation when the equals (=) button is pressed.
    * **`handleClearInput()`**: Clears the display and memory when the C button is pressed.
    * **`handleSignChangeInput()`**: Changes the sign of the number when the +/- button is pressed.
    * **`handleDeleteInput()`**: Deletes the last character when the DEL button is pressed.
    * **`performCalculation()`**: Executes the pending arithmetic operation.
    * **`handleError(String errorMessage)`**: Manages error states and displays them on the screen.
    * **`updateDisplay()`**: Updates the calculator's display screen (JLabel).
    * **`main(String[] args)`**: The main method that launches the application.

## 🔧 Technologies Used

* **Java:** Programming language.
* **Java Swing:** Library for the graphical user interface (GUI).
