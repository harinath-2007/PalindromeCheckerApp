# Palindrome Checker Management System

## 📌 Project Overview

This version of the **Palindrome Checker Management System** checks whether a string is a palindrome **ignoring case differences and spaces**.

This makes the program more practical and suitable for real-world sentences.

---

## 🎯 Use Case: Palindrome Check (Ignoring Case & Spaces)

### Description

In this implementation:

* The input string is:
  `"A man a plan a canal Panama"`
* The string is normalized by:

  * Removing all spaces
  * Converting all characters to lowercase
* A two-pointer approach is used to compare characters from both ends.
* If all characters match → it is a palindrome.

Since the sentence reads the same forward and backward (ignoring spaces and case), it is a palindrome.

---

## 🛠️ Technologies Used

* Java
* JDK 8+
* Regular Expressions (`replaceAll`)
* VS Code / Command Prompt

---

## 📂 Project Structure

```id="normstruct"
PalindromeCheckerApp/
│
└── UseCasePalindromeCheckerApp.java
```

---

## ▶️ How to Compile and Run

### Step 1: Compile

```id="normcompile"
javac UseCasePalindromeCheckerApp.java
```

### Step 2: Run

```id="normrun"
java UseCasePalindromeCheckerApp
```

---

## 🧠 Logic Explanation (Step-by-Step)

### 1️⃣ Normalize the String

```java
String normalized = input.replaceAll("\\s+", "").toLowerCase();
```

* `replaceAll("\\s+", "")` → Removes all spaces
* `toLowerCase()` → Converts to lowercase

Result:

```
amanaplanacanalpanama
```

---

### 2️⃣ Two-Pointer Comparison

* `left = 0`
* `right = length - 1`
* Compare characters from both ends.
* Move inward until `left >= right`.

---

## 🖥️ Sample Output

```id="normoutput"
The given string is a Palindrome (ignoring case & spaces)
```

---

## 📊 Time & Space Complexity

* **Time Complexity:** O(n)
* **Space Complexity:** O(n) (due to normalized string)

---

## 🔍 Why This Version is Better

| Feature         | Benefit                         |
| --------------- | ------------------------------- |
| Ignores case    | Works for uppercase/lowercase   |
| Removes spaces  | Works for full sentences        |
| Practical usage | Real-world palindrome detection |

This is a **real-world ready palindrome checker**.

---

## 🔮 Future Enhancements

* Ignore special characters & punctuation
* Accept user input using `Scanner`
* Combine all palindrome methods in one menu-driven system
* Add unit testing
* Create GUI version

---

## 👨‍💻 Author

HARI NATH KASETTY
