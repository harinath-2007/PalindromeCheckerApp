# Palindrome Checker Management System

## 📌 Project Overview

This version of the **Palindrome Checker Management System** checks whether a string is a palindrome using a **Deque (Double Ended Queue)**.

A Deque allows insertion and removal of elements from **both ends**, making it ideal for palindrome checking.

---

## 🎯 Use Case: Palindrome Check Using Deque

### Description

In this implementation:

* The string `"racecar"` is stored.
* Each character is added to a `Deque`.
* Characters are removed and compared from:

  * Front (`removeFirst()`)
  * Rear (`removeLast()`)
* If both characters match → continue.
* If mismatch occurs → it is NOT a palindrome.
* If all characters match → it is a palindrome.

Since `"racecar"` reads the same forward and backward, it is a palindrome.

---

## 🛠️ Technologies Used

* Java
* JDK 8+
* `java.util.Deque`
* `java.util.ArrayDeque`
* VS Code / Command Prompt

---

## 📂 Project Structure

```id="dequestruct"
PalindromeCheckerApp/
│
└── UseCasePalindromeCheckerApp.java
```

---

## ▶️ How to Compile and Run

### Step 1: Compile

```id="dequecompile"
javac UseCasePalindromeCheckerApp.java
```

### Step 2: Run

```id="dequerun"
java UseCasePalindromeCheckerApp
```

---

## 🧠 Logic Explanation (Step-by-Step)

1. Store the string `"racecar"`.
2. Create a `Deque<Character>`.
3. Add each character using `addLast()`.
4. While the deque has more than one element:

   * Remove first character.
   * Remove last character.
   * Compare both.
5. If mismatch occurs → Not a palindrome.
6. If loop completes successfully → It is a palindrome.

---

## 🖥️ Sample Output

```id="dequeoutput"
The given string is a Palindrome
```

---

## 📊 Time & Space Complexity

* **Time Complexity:** O(n)
* **Space Complexity:** O(n)

---

## 🔍 Why Use Deque?

| Feature                  | Advantage            |
| ------------------------ | -------------------- |
| Remove from both ends    | Efficient comparison |
| No manual reverse needed | Cleaner logic        |
| Direct palindrome logic  | Easy to understand   |

The Deque method is clean, readable, and conceptually strong for understanding double-ended operations.

---

## 🔮 Future Enhancements

* Accept user input using `Scanner`
* Ignore case sensitivity
* Remove spaces & special characters
* Combine all palindrome techniques (Loop, Two-Pointer, Stack, Queue, Deque)
* Add menu-driven interface
* Add unit testing

---

## 👨‍💻 Author

HARI NATH KASETTY
Tell me what you need 👍
