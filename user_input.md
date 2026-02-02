# ⌨️ User Input in Dart

This document explains **how user input works in Dart**, focusing on **console-based applications**.

---

## 1. What Is User Input?

**User input** is any data provided by the user while a program is running. This input allows programs to:

* Interact with users
* Make decisions
* Perform dynamic operations

Examples of input:

* Name
* Age
* Numbers
* Commands

---

## 2. Importing Required Library

To read user input in Dart (console apps), you must import the `dart:io` library.

```dart
import 'dart:io';
```

---

## 3. Reading User Input

Dart uses `stdin.readLineSync()` to read input from the user.

### Example

```dart
print('Enter your name:');
String? name = stdin.readLineSync();
print('Hello, $name');
```

### 🔍 Explanation

* `stdin` → standard input
* `readLineSync()` → reads input as a `String?`
* Input can be `null`, so null-safety is important

---

## 4. Handling Null Safety

Because `readLineSync()` may return `null`, Dart requires null handling.

### Using the `!` operator

```dart
String name = stdin.readLineSync()!;
```

### Using null check

```dart
String? input = stdin.readLineSync();
if (input != null) {
  print(input);
}
```

---

## 5. Converting User Input

User input is always read as a **String**, so conversion is often required.

### String to Integer

```dart
int age = int.parse(stdin.readLineSync()!);
```

### String to Double

```dart
double price = double.parse(stdin.readLineSync()!);
```


---

## 6. Multiple Inputs Example

```dart
print('Enter first number:');
int a = int.parse(stdin.readLineSync()!);

print('Enter second number:');
int b = int.parse(stdin.readLineSync()!);

print('Sum = ${a + b}');
```

---

## 7. Limitations

* Works only for **console applications**
* Not used in Flutter UI apps
* Requires manual validation

---

## 8. Conclusion

User input in Dart is simple and powerful for **command-line applications**. By combining:

* `stdin.readLineSync()`
* Type conversion
* Error handling

Developers can create interactive and reliable programs.


