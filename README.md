# Palindrome Checker Management System

## 📌 Project Overview

This version of the **Palindrome Checker Management System** checks whether a string is a palindrome using both:

* **Stack (LIFO – Last In First Out)**
* **Queue (FIFO – First In First Out)**

By comparing stack and queue outputs, we determine whether the string reads the same forward and backward.

---

## 🎯 Use Case: Palindrome Check Using Stack & Queue

### Description

In this implementation:

* The string `"level"` is stored.
* Each character is:

  * Pushed into a `Stack`
  * Added into a `Queue`
* Characters are removed from both structures:

  * `stack.pop()` → gives characters in reverse order
  * `queue.remove()` → gives characters in original order
* If both match at every step → it is a palindrome.

Since `"level"` reads the same forward and backward, it is a palindrome.

---

## 🛠️ Technologies Used

* Java
* JDK 8+
* `java.util.Stack`
* `java.util.Queue`
* `java.util.LinkedList`
* VS Code / Command Prompt

---

## 📂 Project Structure

```id="stackqueuestruct"
PalindromeCheckerApp/
│
└── UseCasePalindromeCheckerApp.java
```

---

## ▶️ How to Compile and Run

### Step 1: Compile

```id="stackqueuecompile"
javac UseCasePalindromeCheckerApp.java
```

### Step 2: Run

```id="stackqueuerun"
java UseCasePalindromeCheckerApp
```

---

## 🧠 Logic Explanation (Step-by-Step)

1. Store the string `"level"`.
2. Create:

   * `Stack<Character>`
   * `Queue<Character>`
3. Insert each character into both structures.
4. Compare:

   * Pop from stack (reverse order)
   * Remove from queue (original order)
5. If mismatch occurs → Not a palindrome.
6. If all match → It is a palindrome.

---

## 🖥️ Sample Output

```id="stackqueueoutput"
The given string is a Palindrome
```

---

## 📊 Time & Space Complexity

* **Time Complexity:** O(n)
* **Space Complexity:** O(n) (uses both stack and queue)

---

## 🔍 Concept Understanding

| Data Structure | Order | Purpose in Program       |
| -------------- | ----- | ------------------------ |
| Stack          | LIFO  | Reverses the string      |
| Queue          | FIFO  | Maintains original order |

By comparing both, we verify palindrome property.

---

## 🔮 Future Enhancements

* Accept user input using `Scanner`
* Ignore case sensitivity
* Remove spaces & special characters
* Combine all palindrome methods into one application
* Add menu-driven interface

---

## 👨‍💻 Author

HARI NATH KASETTY
