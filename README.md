# Palindrome Checker Management System

## 📌 Project Overview

This version of the **Palindrome Checker Management System** follows an **Object-Oriented Programming (OOP)** approach.

Instead of writing all logic inside the `main()` method, the palindrome logic is separated into a **service class** called:

```
PalindromeService
```

This improves code structure, reusability, and maintainability.

---

## 🎯 Use Case: Palindrome Check Using OOP Design

### Description

In this implementation:

* A separate class `PalindromeService` is created.
* The method `isPalindrome(String input)` contains the palindrome logic.
* The `main()` method:

  * Creates an object of `PalindromeService`
  * Calls the `isPalindrome()` method
  * Prints the result

This design follows the principle of **Separation of Concerns**.

---

## 🛠️ Technologies Used

* Java
* JDK 8+
* OOP Concepts (Classes & Methods)
* VS Code / Command Prompt

---

## 📂 Project Structure

```id="oopstruct"
PalindromeCheckerApp/
│
└── UseCasePalindromeCheckerApp.java
```

Inside the file:

```
- PalindromeService (Logic Layer)
- UseCasePalindromeCheckerApp (Presentation Layer)
```

---

## ▶️ How to Compile and Run

### Step 1: Compile

```id="oopcompile"
javac UseCasePalindromeCheckerApp.java
```

### Step 2: Run

```id="ooprun"
java UseCasePalindromeCheckerApp
```

---

## 🧠 Logic Explanation

### 🔹 PalindromeService Class

```java id="ooplogic"
public boolean isPalindrome(String input)
```

* Uses two-pointer approach
* Compares characters from both ends
* Returns:

  * `true` → if palindrome
  * `false` → if not

---

### 🔹 Main Class

* Creates object:

  ```
  PalindromeService service = new PalindromeService();
  ```
* Calls:

  ```
  service.isPalindrome(input);
  ```
* Prints result

---

## 🖥️ Sample Output

```id="oopoutput"
The given string is a Palindrome (OOP Design)
```

---

## 📊 Time & Space Complexity

* **Time Complexity:** O(n)
* **Space Complexity:** O(1)

---

## 🔍 Why This Version is Best for Projects?

| Feature         | Benefit                       |
| --------------- | ----------------------------- |
| Separate class  | Clean architecture            |
| Reusable method | Can be used in other programs |
| Easy testing    | Supports unit testing         |
| Follows OOP     | Industry standard approach    |

This version is **professional and industry-ready** compared to earlier implementations.

---

## 🔮 Future Enhancements

* Add user input using `Scanner`
* Add exception handling
* Create multiple service classes
* Convert into Spring Boot REST API
* Add JUnit testing
* Create GUI version

---

## 👨‍💻 Author

HARI NATH KASETTY
