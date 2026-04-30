# Aegis Identity Generator 🛡️

A Java-based security terminal simulation that handles user registration, data sanitization, and identity verification. This project was built to practice core Java logic and mathematical operations.

## 🚀 Features
- **Input Sanitization**: Uses `.trim()` and `.toLowerCase()` to clean user data.
- **Security Check**: Blocks restricted keywords like "admin" or "root".
- **Key Verification**: Logic-based matching using `charAt()` and `Character.toUpperCase()`.
- **Dynamic Stats**: Uses `Math.sqrt()` and `Math.pow()` to generate randomized "Power Levels."
- **Data Sync Simulation**: Uses `equalsIgnoreCase()` to handle flexible user confirmations.

## 🛠️ Java Tools Used
- **Variables**: `String`, `double`, `char`, `int`.
- **Input/Output**: `Scanner` for user input and `System.out.printf` for formatted output.
- **Math Library**: `Math.pow`, `Math.sqrt`, and `Random` class.
- **Logic Control**: Nested `if-else` statements and Logical Operators (`||`, `&&`).
- **Validation**: `isEmpty()` and `length()` checks for robust error handling.

## 📂 Project Structure
- **File**: `AegisGenerator.java`
- **Package**: `project`

## 💻 How To Run
1. Save the code as `AegisGenerator.java`.
2. Open your terminal and compile:
   ```bash
   javac AegisGenerator.java
   ```
3. Run the application:
   ```bash
   java AegisGenerator
   ```

---
*Created as part of my Java Learning Journey.*
