# Palindrome Checker Management System

## 📌 Project Overview

This version of the **Palindrome Checker Management System** checks whether a string is a palindrome using the **Recursion technique**.

Instead of using loops or data structures, this approach uses a recursive function that compares characters from both ends of the string.

---

## 🎯 Use Case: Palindrome Check Using Recursion

### Description

In this implementation:

* The string `"level"` is stored.
* A recursive method `isPalindrome()` is created.
* The method compares:

  * Left character (`left`)
  * Right character (`right`)
* If both match → recursive call moves inward.
* If mismatch occurs → return `false`.
* If `left >= right` → return `true` (base case).

Since `"level"` reads the same forward and backward, it is a palindrome.

---

## 🛠️ Technologies Used

* Java
* JDK 8+
* VS Code / Command Prompt

---

## 📂 Project Structure

```id="recursivestruct"
PalindromeCheckerApp/
│
└── UseCasePalindromeCheckerApp.java
```

---

## ▶️ How to Compile and Run

### Step 1: Compile

```id="recursivecompile"
javac UseCasePalindromeCheckerApp.java
```

### Step 2: Run

```id="recursiverun"
java UseCasePalindromeCheckerApp
```

---

## 🧠 Logic Explanation (Step-by-Step)

### Recursive Function:

```java
public static boolean isPalindrome(String str, int left, int right)
```

### Steps:

1. **Base Case**
   If `left >= right` → return `true` (all characters matched).

2. **Mismatch Case**
   If `str.charAt(left) != str.charAt(right)` → return `false`.

3. **Recursive Call**
   Move inward:

   ```
   isPalindrome(str, left + 1, right - 1)
   ```

This continues until the base condition is reached.

---

## 🖥️ Sample Output

```id="recursiveoutput"
The given string is a Palindrome
```

---

## 📊 Time & Space Complexity

* **Time Complexity:** O(n)
* **Space Complexity:** O(n) (due to recursive call stack)

---

## 🔍 Why Use Recursion?

| Feature                  | Advantage                   |
| ------------------------ | --------------------------- |
| Clean logic              | Easy to understand          |
| No extra data structures | Simple implementation       |
| Conceptual clarity       | Good for learning recursion |

Recursion is elegant but uses additional memory due to function call stack.

---

## 🔮 Future Enhancements

* Accept user input using `Scanner`
* Ignore case sensitivity
* Remove spaces & special characters
* Combine all palindrome methods into one system
* Add menu-driven interface
* Add unit testing

---

## 👨‍💻 Author

HARI NATH KASETTY
