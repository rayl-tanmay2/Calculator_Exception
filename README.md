# Calculator_Exception
# 🧮 Java Console Calculator

[![Java](https://img.shields.io/badge/Java-17-blue.svg)](https://www.oracle.com/java/)  
A **console-based calculator** built in **Java** featuring basic arithmetic and advanced mathematical operations. The program is fully modular, well-commented, and includes exception handling for robust performance.

---

## 👤 Student Information

| Field       | Details            |
|-------------|--------------------|
| **Name**    | _Your Name_        |
| **PRN**     | _Your PRN_         |
| **Batch**   | _Your Batch_       |

---

## Features

-  Addition  
-  Subtraction  
-  Multiplication  
-  Division (with divide-by-zero handling)  
-  Square  
-  Cube  
-  Square Root (with negative input validation)  

---

## Project Structure

```
CalculatorApp/
├── MainCalculator.java       // Main driver with menu
├── Addition.java             // Handles addition logic
├── Subtraction.java          // Handles subtraction logic
├── Multiplication.java       // Handles multiplication logic
├── Division.java             // Handles division logic
├── Square.java               // Handles square logic
├── Cube.java                 // Handles cube logic
├── SquareRoot.java           // Handles square root logic
```

Each operation is encapsulated in a separate class, maintaining clean and maintainable code.

---

### 📥 Clone the Repository

```bash
git clone https://github.com/rayl-tanmay2/java-console-calculator.git
cd java-console-calculator
```

### Prerequisites

- Java JDK (8 or above)

### Compile

```bash
javac *.java
```

### Run

```bash
java MainCalculator
```

---

## Sample Output

```bash
--- Calculator Menu ---
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Square
6. Cube
7. Square Root
8. Exit
Enter your choice: 1
Enter first number: 10
Enter second number: 5
Result = 15.0
```

---

## 🛡️ Exception Handling

The application uses built-in exception handling for a smooth user experience:

| Exception                | Handled Scenario                           |
|--------------------------|--------------------------------------------|
| `InputMismatchException` | When user enters non-numeric input         |
| `ArithmeticException`    | Division by zero or square root of negative|
| `Exception`              | Any other unexpected error                 |

---

##  Coding Standards Followed

- Clean class/method names (`CamelCase`)
- Modular structure (one class per operation)
- In-code comments for clarity
- Proper indentation and formatting
- Descriptive variable names

---

##  Future Enhancements

- GUI version using JavaFX or Swing  
- History of previous calculations  
- Scientific calculator functions (log, sin, cos)  
- Unit testing with JUnit  

---

## License

This project is developed for educational purposes only.  
Feel free to use or modify it for your learning needs.

---

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss your proposed improvements.

---

