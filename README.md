Haklısınız, projelerinizi uluslararası bir kitleye ulaştırmak ve daha fazla kişi tarafından anlaşılır kılmak için README dosyasını İngilizce hazırlamak genellikle daha iyi bir pratiktir.

İşte bir önceki Türkçe README içeriğinin İngilizce çevirisi:

Markdown

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

(You can add a screenshot of your running calculator here. For example: `![Calculator Screenshot](screenshot.png)`)

## 🛠️ Setup and Running

To run this project, you need to have the Java Development Kit (JDK) installed on your system.

1.  **Clone the Repository (optional):**
    ```bash
    git clone [https://github.com/](https://github.com/)[YourGitHubUsername]/[YourProjectName].git
    cd [YourProjectName]
    ```
2.  **Compilation and Execution:**
    * If you are using an IDE (like IntelliJ IDEA, Eclipse, etc.), open the project and run the `main` method in the `Calculator.java` file.
    * To compile and run from the command line:
        ```bash
        # In the project's root directory (where Calculator.java is located)
        javac Calculator.java
        java Calculator
        ```
        If your `Calculator.java` file is inside a package (e.g., `package com.example;`), the compilation and execution commands should be adjusted accordingly. For instance, if the file is at `com/example/Calculator.java` and has the `package com.example;` declaration:
        ```bash
        # Assuming you are in the src directory (src/com/example/Calculator.java)
        javac com/example/Calculator.java
        java com.example.Calculator
        ```
        However, as the code you shared does not have a package declaration, the first method is applicable.

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
