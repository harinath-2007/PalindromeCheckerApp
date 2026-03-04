# Palindrome Checker Management System

## 📌 Project Overview

This project is part of the **Palindrome Checker Management System**.

**UC3** demonstrates how to check whether a string is a palindrome by:

* Reversing the string using a `for` loop
* Comparing the reversed string with the original
* Printing the result in the console

---

## 🎯 Use Case 3: Palindrome Check Using Loop

### Description

In this use case:

* A string (`"level"`) is stored in a variable.
* The string is reversed manually using a loop.
* The original and reversed strings are compared.
* The result is displayed.

---

## 🛠️ Technologies Used

* Java
* JDK 8+
* VS Code / Command Prompt

---

## 📂 Project Structure

```id="uc3struct"
PalindromeCheckerApp/
│
└── UseCase3PalindromeCheckerApp.java
```

---

## ▶️ How to Compile and Run

### Step 1: Compile the Program

```id="uc3compile"
javac UseCase3PalindromeCheckerApp.java
```

### Step 2: Run the Program

```id="uc3run"
java UseCase3PalindromeCheckerApp
```

---

## 🧠 Logic Explanation

1. Store the string `"level"` in a variable.
2. Use a `for` loop to iterate from the last character to the first.
3. Build the reversed string.
4. Compare original string with reversed string using `equals()`.
5. Display whether it is a palindrome or not.

---

## 🖥️ Sample Output

```id="uc3output"
The given string is a Palindrome
```

---

## 📘 What is a Palindrome?

A **palindrome** is a word, number, or phrase that reads the same forward and backward.

### Examples:

* level
* madam
* radar
* 121

---

## 🔮 Future Enhancements

* Accept user input using `Scanner`
* Make comparison case-insensitive
* Ignore spaces and special characters
* Optimize using `StringBuilder`
* Create menu-driven system combining UC1, UC2, UC3

---

## 👨‍💻 Author

HARI NATH KASETTY
