# 📟 Java Console Calculator

This is a simple and interactive **Java Console Calculator** built as part of the **Elevate Labs Java Developer Internship** task. It allows users to perform basic arithmetic operations using Java console I/O.

---

## 📌 Task Overview

**Task 1: Java Console Calculator**

- **Objective:** Build a basic calculator using Java console I/O.
- **Tools Used:**  
  - Java JDK  
  - Code Editor: VS Code / IntelliJ IDEA CE  
  - Terminal / Command Prompt  
- **Deliverables:** Java source code (`ConsoleCalculator.java`)

---

## 🧾 Features

✅ Addition  
✅ Subtraction  
✅ Multiplication  
✅ Division  
✅ Error handling for division by zero  
✅ Loop to allow repeated operations until user exits

---

## 📂 File Structure

```
📁 
└── Calculator.java   // Main Java file containing calculator logic
└── README.md                // Documentation file (this file)
```

---

## 🔍 Code Explanation

```java
public class ConsoleCalculator
```
This is the main class containing all calculator methods and logic.

### ➕ Arithmetic Methods

```java
public static double add(double a, double b)
```
Each operation like `add`, `subtract`, `multiply`, `divide` is defined in a separate method for modularity and reusability.

### 🔁 User Input Loop

```java
while (continueCalc) { ... }
```
A loop allows the user to continue performing calculations until they choose to exit.

### 🧠 Input Handling

```java
Scanner scanner = new Scanner(System.in);
```
`Scanner` is used to take user input from the console (numbers and operation choices).

### ❌ Exit Option

```java
if (choice == 5) {
    continueCalc = false;
    ...
}
```
Gives the user an option to exit cleanly from the calculator.

---

## 🚀 How to Run

### Prerequisites
- Java JDK installed and added to system path
- A terminal/command prompt
- VS Code / IntelliJ or any Java editor (optional)

### Steps

1. Clone or download this repository.
2. Open terminal in the directory where `ConsoleCalculator.java` is saved.
3. Compile the code:
   ```bash
   javac ConsoleCalculator.java
   ```
4. Run the program:
   ```bash
   java ConsoleCalculator
   ```

---

## 🎯 Outcome

- Understand basic Java syntax and method structure.
- Learn console-based input/output operations.
- Implement control structures (`if`, `switch`, `while` loops).
- Gain confidence in logic building and modular programming.

---

## 👨‍💻 Author

**Kshitij Jha**  
Java Developer Intern | Elevate Labs
