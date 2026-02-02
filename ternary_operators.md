# ❓ Ternary Operator in Dart

<br><br>


## 1. What Is the Ternary Operator?

The **ternary operator** is a **short form of an if-else statement**. It allows you to make decisions in a **single line of code**.

---

## 2. Syntax

```dart
condition ? value_if_true : value_if_false;
```

### 🔍 Explanation

* `condition` → expression that returns `true` or `false`
* `value_if_true` → executed if condition is `true`
* `value_if_false` → executed if condition is `false`

---

## 3. Basic Example

```dart
int a = 10;
int b = 20;

int max = (a > b) ? a : b;
print(max); // Output: 20
```

---

## 4. Ternary Operator vs if-else

### Using if-else

```dart
String result;
if (a > b) {
  result = 'a is greater';
} else {
  result = 'b is greater';
}
```

### Using Ternary Operator

```dart
String result = (a > b) ? 'a is greater' : 'b is greater';
```

✔ Same result with **less code**

---

## 5. Using Ternary Operator with User Input

```dart
import 'dart:io';

print('Enter a number:');
int number = int.parse(stdin.readLineSync()!);

String type = (number % 2 == 0) ? 'Even' : 'Odd';
print(type);
```

---

## 6. Nested Ternary Operator

Ternary operators can be nested, but should be used carefully.

```dart
int score = 85;

String grade = (score >= 90)
    ? 'A'
    : (score >= 75)
        ? 'B'
        : 'C';
```

⚠️ Too much nesting can reduce readability.

---

## 7. When to Use Ternary Operator

✅ Use when:

* Condition is simple
* Improves readability

❌ Avoid when:

* Logic is complex
* Multiple conditions are involved

---

## 8. Common Mistakes

* Forgetting `:`
* Using complex logic inside ternary
* Overusing nested ternary operators

---

## 9. Conclusion

The ternary operator is a **powerful and concise tool** for conditional logic in Dart. When used correctly, it:

* Reduces code size
* Improves readability
* Replaces simple if-else statements


