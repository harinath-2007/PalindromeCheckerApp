# Palindrome Checker Management System

## 📌 Project Overview

This version of the **Palindrome Checker Management System** checks whether a string is a palindrome using the **Stack data structure** in Java.

A stack follows the **LIFO (Last In, First Out)** principle, which makes it useful for reversing data.

---

## 🎯 Use Case: Palindrome Check Using Stack

### Description

In this implementation:

* The string `"madam1"` is stored in a variable.
* Each character is pushed into a `Stack`.
* Characters are popped from the stack (which reverses the order).
* The popped characters are compared with the original string.
* If all characters match → it is a palindrome.
* If mismatch occurs → it is NOT a palindrome.

Since `"madam1"` is not the same forward and backward, the output will indicate that it is NOT a palindrome.

---

## 🛠️ Technologies Used

* Java
* JDK 8+
* `java.util.Stack`
* VS Code / Command Prompt

---

## 📂 Project Structure

```id="stackstruct"
PalindromeCheckerApp/
│
└── UseCasePalindromeCheckerApp.java
```

---

## ▶️ How to Compile and Run

### Step 1: Compile

```id="stackcompile"
javac UseCasePalindromeCheckerApp.java
```

### Step 2: Run

```id="stackrun"
java UseCasePalindromeCheckerApp
```

---

## 🧠 Logic Explanation (Step-by-Step)

1. Store the string `"madam1"`.
2. Create a `Stack<Character>`.
3. Push each character into the stack.
4. Pop characters one by one.
5. Compare popped character with original string character.
6. If mismatch occurs → set `isPalindrome = false`.
7. Print result.

---

## 🖥️ Sample Output

```id="stackoutput"
The given string is NOT a Palindrome
```

---

## 📊 Time & Space Complexity

* **Time Complexity:** O(n)
* **Space Complexity:** O(n) (extra stack used)

---

## 🔍 Comparison with Other Methods

| Method         | Extra Space | Efficiency |
| -------------- | ----------- | ---------- |
| Reverse String | Yes         | Good       |
| Two-Pointer    | No          | Best       |
| Stack Method   | Yes         | Moderate   |

---

## 🔮 Future Enhancements

* Accept user input using `Scanner`
* Ignore case sensitivity
* Remove special characters
* Convert into menu-driven system
* Combine all use cases (UC1–UC5)

---

## 👨‍💻 Author

HARI NATH KASETTY
