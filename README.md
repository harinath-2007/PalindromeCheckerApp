# Palindrome Checker Management System

## 📌 Project Overview

This version of the **Palindrome Checker Management System** implements the **Strategy Design Pattern**.

The Strategy Pattern allows selecting different palindrome checking algorithms at runtime without modifying the main application logic.

This is a **professional OOP design approach** used in real-world software systems.

---

## 🎯 Use Case: Palindrome Check Using Strategy Pattern

### 🔹 What is Strategy Pattern?

The **Strategy Pattern** defines a family of algorithms, encapsulates each one, and makes them interchangeable.

Here:

* Each palindrome checking method is a separate strategy.
* The main application chooses which strategy to use.

---

## 🏗️ Architecture

### 1️⃣ Strategy Interface

```id="strategyinterface"
interface PalindromeStrategy {
    boolean isPalindrome(String input);
}
```

This defines a common contract for all palindrome algorithms.

---

### 2️⃣ Concrete Strategies

#### ✅ TwoPointerStrategy

* Uses two-pointer approach
* Efficient (O(n), O(1))

#### ✅ ReverseStringStrategy

* Uses `StringBuilder.reverse()`
* Simple & readable

---

### 3️⃣ Context Class (Main Class)

```id="strategycontext"
PalindromeStrategy strategy = new TwoPointerStrategy();
```

You can switch strategies easily:

```id="strategyswitch"
PalindromeStrategy strategy = new ReverseStringStrategy();
```

No other code changes required.

---

## 🛠️ Technologies Used

* Java
* JDK 8+
* OOP Concepts
* Design Patterns (Strategy Pattern)
* VS Code / Command Prompt

---

## 📂 Project Structure

```id="strategystruct"
PalindromeCheckerApp/
│
└── UseCasePalindromeCheckerApp.java
```

Inside the file:

```id="strategyinside"
- PalindromeStrategy (Interface)
- TwoPointerStrategy (Concrete Strategy 1)
- ReverseStringStrategy (Concrete Strategy 2)
- UseCasePalindromeCheckerApp (Context / Main Class)
```

---

## ▶️ How to Compile and Run

### Step 1: Compile

```id="strategycompile"
javac UseCasePalindromeCheckerApp.java
```

### Step 2: Run

```id="strategyrun"
java UseCasePalindromeCheckerApp
```

---

## 🖥️ Sample Output

```id="strategyoutput"
The given string is a Palindrome (Strategy Pattern)
```

---

## 📊 Time & Space Complexity

| Strategy              | Time | Space |
| --------------------- | ---- | ----- |
| TwoPointerStrategy    | O(n) | O(1)  |
| ReverseStringStrategy | O(n) | O(n)  |

---

## 🔍 Why Strategy Pattern is Important?

| Benefit               | Explanation                                      |
| --------------------- | ------------------------------------------------ |
| Open/Closed Principle | Add new strategy without modifying existing code |
| Clean Architecture    | Separation of concerns                           |
| Flexible              | Switch algorithms at runtime                     |
| Scalable              | Easily add Stack, Recursion, Deque strategies    |

This is an **industry-level design pattern implementation**.

---

## 🔮 Future Enhancements

* Add more strategies:

  * StackStrategy
  * RecursionStrategy
  * DequeStrategy
* Add user input selection (menu-based strategy choice)
* Convert into Spring Boot REST API
* Add unit testing (JUnit)
* Add GUI interface

---

## 👨‍💻 Author

HARI NATH KASETTY
