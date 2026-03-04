# Palindrome Checker Management System

## 📌 Project Overview

This version of the **Palindrome Checker Management System** checks whether a given string is a palindrome using the **Two-Pointer Technique**.

Instead of reversing the string, this approach compares characters from both ends moving towards the center.

---

## 🎯 Use Case: Palindrome Check Using Two Pointers

### Description

In this implementation:

* The string `"radar"` is stored in a variable.
* The string is converted into a character array.
* Two pointers (`left` and `right`) are used.
* Characters are compared from both ends.
* If all characters match → it is a palindrome.
* If any mismatch occurs → it is not a palindrome.

---

## 🛠️ Technologies Used

* Java
* JDK 8+
* VS Code / Command Prompt

---

## 📂 Project Structure

```id="twopointerstruct"
PalindromeCheckerApp/
│
└── UseCasePalindromeCheckerApp.java
```

---

## ▶️ How to Compile and Run

### Step 1: Compile

```id="twopointercompile"
javac UseCasePalindromeCheckerApp.java
```

### Step 2: Run

```id="twopointerrun"
java UseCasePalindromeCheckerApp
```

---

## 🧠 Logic Explanation (Step-by-Step)

1. Store the string `"radar"`.
2. Convert it to a character array using `toCharArray()`.
3. Initialize:

   * `left = 0`
   * `right = length - 1`
4. Compare:

   * `characters[left]` with `characters[right]`
5. Move:

   * `left++`
   * `right--`
6. Stop when:

   * `left >= right`
   * Or mismatch found.

This approach is **more efficient** because:

* It does not create a new reversed string.
* It checks only half of the characters.
* Time Complexity: **O(n)**
* Space Complexity: **O(1)**

---

## 🖥️ Sample Output

```id="twopointeroutput"
The given string is a Palindrome
```

---

## 📘 Why Two-Pointer Method is Better?

| Method         | Extra Space       | Efficiency |
| -------------- | ----------------- | ---------- |
| Reverse String | Uses extra string | Good       |
| Two-Pointer    | No extra string   | Better     |

---

## 🔮 Future Enhancements

* Take user input using `Scanner`
* Ignore uppercase/lowercase differences
* Remove spaces and special characters
* Build a menu-driven system (UC1–UC4)
* Add unit testing

---

## 👨‍💻 Author

HARI NATH KASETTY
