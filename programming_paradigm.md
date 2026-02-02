# 🧠 Programming Paradigm



<br>
<br>

## 1. What Is a Programming Paradigm?

A **programming paradigm** is a **style or way of thinking** about how programs are written and structured.

It defines:

* How code is organized
* How problems are solved
* How programs execute logic

👉 In simple words:
A programming paradigm is **how you think when you write code**.

---

## 2. Why Programming Paradigms Matter

Programming paradigms help developers:

* Write cleaner and more organized code
* Solve problems efficiently
* Choose the right tools for the job
* Understand different programming languages faster

---

## 3. Main Types of Programming Paradigms

### 3.1 Procedural Programming

📌 Focuses on **procedures (functions)** that operate on data.

#### Characteristics

* Step-by-step instructions
* Uses functions and variables

#### Example (Dart)

```dart
void greet() {
  print('Hello');
}

greet();
```

---

### 3.2 Object-Oriented Programming (OOP)

📌 Focuses on **objects** that contain data and behavior.

#### Key Concepts

* Class
* Object
* Encapsulation
* Inheritance
* Polymorphism

#### Example (Dart)

```dart
class Person {
  String name;
  Person(this.name);
}

Person p = Person('Ali');
```

---

### 3.3 Functional Programming

📌 Focuses on **functions and immutability**.

#### Characteristics

* Functions are first-class citizens
* Avoids changing data
* Uses expressions instead of statements

#### Example (Dart)

```dart
int add(int a, int b) => a + b;
```

---

### 3.4 Declarative Programming

📌 Focuses on **what the program should do**, not how to do it.

#### Example

```dart
var evenNumbers = numbers.where((n) => n % 2 == 0);
```

Flutter UI is mostly **declarative**.

---

## 4. Multi-Paradigm Languages

Many modern languages support **multiple paradigms**.

### Examples

| Language | Paradigms                    |
| -------- | ---------------------------- |
| Dart     | OOP, Functional, Declarative |
| Java     | OOP, Procedural              |
| Python   | OOP, Functional, Procedural  |

---

## 6. Conclusion

A programming paradigm is a **fundamental concept** in software development that defines how developers think and write code.

Understanding paradigms helps you:

* Become a better programmer
* Learn new languages faster
* Write more maintainable applications

