# Palindrome Checker Management System

## 📌 Project Overview

This version of the **Palindrome Checker Management System** checks whether a string is a palindrome using the **LinkedList** data structure in Java.

Since `LinkedList` allows operations at both the beginning and the end, it can efficiently compare characters from both sides.

---

## 🎯 Use Case: Palindrome Check Using LinkedList

### Description

In this implementation:

* The string `"madam"` is stored.
* Each character is added into a `LinkedList`.
* Characters are removed and compared from:

  * First (`removeFirst()`)
  * Last (`removeLast()`)
* If characters match → continue checking.
* If mismatch occurs → it is NOT a palindrome.
* If all match → it is a palindrome.

Since `"madam"` reads the same forward and backward, it is a palindrome.

---

## 🛠️ Technologies Used

* Java
* JDK 8+
* `java.util.LinkedList`
* VS Code / Command Prompt

---

## 📂 Project Structure

```id="linkedliststruct"
PalindromeCheckerApp/
│
└── UseCasePalindromeCheckerApp.java
```

---

## ▶️ How to Compile and Run

### Step 1: Compile

```id="linkedlistcompile"
javac UseCasePalindromeCheckerApp.java
```

### Step 2: Run

```id="linkedlistrun"
java UseCasePalindromeCheckerApp
```

---

## 🧠 Logic Explanation (Step-by-Step)

1. Store the string `"madam"`.
2. Create a `LinkedList<Character>`.
3. Add each character into the list.
4. While the list size is greater than 1:

   * Remove first character.
   * Remove last character.
   * Compare both.
5. If mismatch occurs → Not a palindrome.
6. If loop completes successfully → It is a palindrome.

---

## 🖥️ Sample Output

```id="linkedlistoutput"
The given string is a Palindrome
```

---

## 📊 Time & Space Complexity

* **Time Complexity:** O(n)
* **Space Complexity:** O(n)

---

## 🔍 Why Use LinkedList?

| Feature                 | Advantage                |
| ----------------------- | ------------------------ |
| removeFirst()           | Efficient front removal  |
| removeLast()            | Efficient rear removal   |
| Doubly linked structure | Easy two-side comparison |

This method is conceptually similar to the **Deque approach**, but directly uses `LinkedList`.

---

## 🔮 Future Enhancements

* Accept user input using `Scanner`
* Ignore case sensitivity
* Remove special characters & spaces
* Combine all palindrome methods into one project
* Add menu-driven system
* Implement unit testing

---

## 👨‍💻 Author

HARI NATH KASETTY
