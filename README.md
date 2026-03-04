# Palindrome Checker Management System

## 📌 Project Overview

This version of the **Palindrome Checker Management System** compares the performance of two palindrome checking methods:

* ✅ Two Pointer Method
* ✅ Reverse String Method

The program also measures execution time using:

```java
System.nanoTime()
```

This helps analyze which method is more efficient.

---

## 🎯 Use Case: Performance Comparison of Methods

### Description

In this implementation:

1. The input string:

   ```
   "A man a plan a canal Panama"
   ```

2. The string is normalized by:

   * Removing spaces
   * Converting to lowercase

3. Two methods are tested:

   * `twoPointerMethod()`
   * `reverseMethod()`

4. Execution time is measured in **nanoseconds (ns)**.

---

## 🛠️ Technologies Used

* Java
* JDK 8+
* `System.nanoTime()` for performance measurement
* StringBuilder
* VS Code / Command Prompt

---

## 📂 Project Structure

```id="performancestruct"
PalindromeCheckerApp/
│
└── UseCasePalindromeCheckerApp.java
```

---

## ▶️ How to Compile and Run

### Step 1: Compile

```id="performancecompile"
javac UseCasePalindromeCheckerApp.java
```

### Step 2: Run

```id="performancerun"
java UseCasePalindromeCheckerApp
```

---

## 🧠 Logic Explanation

### 🔹 Two Pointer Method

* Compare characters from both ends.
* Move inward.
* Stops on mismatch.

✔ Time Complexity: **O(n)**
✔ Space Complexity: **O(1)**

---

### 🔹 Reverse Method

* Reverse string using:

  ```java
  new StringBuilder(input).reverse().toString();
  ```
* Compare with original string.

✔ Time Complexity: **O(n)**
✔ Space Complexity: **O(n)**

---

### 🔹 Performance Measurement

```java
long start = System.nanoTime();
...
long end = System.nanoTime();
```

Execution time = `end - start`

Measured in **nanoseconds (ns)**.

---

## 🖥️ Sample Output

```id="performanceoutput"
Two Pointer Result: true
Two Pointer Time: 4200 ns
Reverse Method Result: true
Reverse Method Time: 8500 ns
```

*(Time may vary depending on system performance.)*

---

## 📊 Comparison Table

| Method         | Time Complexity | Space Complexity | Faster?           |
| -------------- | --------------- | ---------------- | ----------------- |
| Two Pointer    | O(n)            | O(1)             | ✅ Usually Faster  |
| Reverse Method | O(n)            | O(n)             | ❌ Slightly Slower |

---

## 🔍 Key Learning

* Both methods are efficient.
* Two-pointer method is more memory efficient.
* `System.nanoTime()` is useful for micro-performance testing.
* Real-world benchmarking should run multiple iterations for accuracy.

---

## 🔮 Future Enhancements

* Run performance test in loop (1000 iterations) for accurate benchmarking
* Add more methods (Stack, Recursion, Deque)
* Display average execution time
* Convert into benchmarking mini-tool
* Create graphical performance chart

---

## 👨‍💻 Author

HARI NATH KASETTY
