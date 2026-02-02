# ⚠️ Error Types in Software Development

This document provides a **research-style overview of common error types in software development**.
---

## 1. What Is an Error?

An **error** is any issue that causes a program to:

* Crash ❌
* Produce incorrect results ❌
* Behave unexpectedly ❌

Errors can occur at **any stage** of software development—from writing code to runtime execution.

---

## 2. Syntax Errors

### 🧩 Definition

Syntax errors occur when the code violates the **rules of the programming language**.

### 📌 Examples

* Missing semicolon
* Misspelled keywords
* Incorrect brackets or parentheses

```dart
print("Hello World"  // Missing closing parenthesis
```

### 🛑 When They Occur

* At **compile time**

### ✅ How to Fix

* Follow language syntax rules
* Use IDE error highlighting

---

## 3. Compile-Time Errors

### 🧩 Definition

Errors detected by the compiler **before the program runs**.

### 📌 Examples

* Type mismatch
* Undefined variables
* Missing imports

```dart
int x = "hello"; // Type mismatch
```

### 🛑 Impact

* Program cannot be compiled

---

## 4. Runtime Errors

### 🧩 Definition

Errors that occur **while the program is running**.

### 📌 Examples

* Division by zero
* Null reference
* File not found

```dart
int x = 10 ~/ 0; // Runtime error
```

### 🛑 Impact

* App crashes during execution

---

## 5. Logical Errors

### 🧩 Definition

Errors where the program **runs without crashing** but produces **wrong output**.

### 📌 Example

```dart
int sum(int a, int b) {
  return a - b; // Logic error
}
```

### ❗ Why They Are Dangerous

* Hard to detect
* No compiler warnings

### ✅ How to Fix

* Debugging
* Writing test cases

---

## 6. Runtime Exceptions

### 🧩 Definition

Unexpected events that disrupt normal program flow.

### 📌 Common Examples

* NullPointerException
* IndexOutOfRangeException
* TimeoutException

```dart
List<int> nums = [1, 2];
print(nums[5]); // Exception
```

---

## 7. Input Errors

### 🧩 Definition

Errors caused by **invalid or unexpected user input**.

### 📌 Examples

* Entering text instead of numbers
* Empty input fields

### ✅ Solution

* Input validation
* Error messages

---

## 8. Resource Errors

### 🧩 Definition

Errors caused by insufficient system resources.

### 📌 Examples

* Memory overflow
* File handle limits
* Network failure

---

## 9. Environment Errors

### 🧩 Definition

Errors related to the **system or environment** where the app runs.

### 📌 Examples

* Missing SDK
* Wrong OS version
* Incorrect environment variables

---

## 10. Platform-Specific Errors

### 🧩 Definition

Errors that occur only on specific platforms.

### 📌 Examples

* Android permission errors
* iOS build signing issues
* Web CORS errors

---

## 11. Errors in Mobile Development (Flutter Example)

### 📱 Common Flutter Errors

* Widget overflow
* BuildContext misuse
* Null safety issues

```dart
setState(() {}); // Called after dispose()
```

---

## 12. Comparison Table

| Error Type   | Detected When | Causes Crash |
| ------------ | ------------- | ------------ |
| Syntax       | Compile time  | ❌            |
| Compile-time | Compile time  | ❌            |
| Runtime      | Runtime       | ✅            |
| Logical      | Runtime       | ❌            |
| Exception    | Runtime       | ✅            |

---

## 13. How to Reduce Errors

* ✅ Use clean code practices
* 🧪 Write unit tests
* 🐞 Debug frequently
* 📘 Read error logs carefully
* 🔁 Refactor code regularly

---

## 14. Conclusion

Understanding error types helps developers:

* Debug faster
* Write safer code
* Build reliable applications

Errors are **not failures**, but **learning opportunities** in software development.

---

## 📚 References

* Programming Fundamentals
* Software Engineering Concepts
* Flutter & Dart Documentation

---

✨ *Prepared for educational and research purposes*
