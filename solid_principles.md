# 🧱 SOLID Principles in Software Engineering

This document explains the **SOLID principles**, which are five fundamental guidelines for writing **clean, maintainable, and scalable object-oriented code**. 

<br>
<br>

## 1. What Are SOLID Principles?

**SOLID** is an acronym representing **five design principles** introduced by **Robert C. Martin (Uncle Bob)**.

These principles help developers:

* Reduce code complexity
* Improve readability
* Make code easier to maintain and extend
* Avoid tight coupling

---

## 2. S — Single Responsibility Principle (SRP)

### 📌 Definition

A class should have **only one reason to change**.

👉 This means a class should do **one job only**.

### ❌ Bad Example

```dart
class User {
  void saveUser() {}
  void sendEmail() {}
}
```

### ✅ Good Example

```dart
class User {
  String name;
  User(this.name);
}

class UserRepository {
  void save(User user) {}
}

class EmailService {
  void sendEmail(User user) {}
}
```

---

## 3. O — Open/Closed Principle (OCP)

### 📌 Definition

Software entities should be **open for extension but closed for modification**.

👉 You should be able to add new behavior **without changing existing code**.

### Example

```dart
abstract class Shape {
  double area();
}

class Rectangle extends Shape {
  double width, height;
  Rectangle(this.width, this.height);
  double area() => width * height;
}

class Circle extends Shape {
  double radius;
  Circle(this.radius);
  double area() => 3.14 * radius * radius;
}
```

---

## 4. L — Liskov Substitution Principle (LSP)

### 📌 Definition

Objects of a superclass should be **replaceable with objects of its subclasses** without breaking the program.

👉 Child classes must behave like their parent classes.

### Example

```dart
abstract class Bird {
  void move();
}

class Sparrow extends Bird {
  void move() => print('Flying');
}
```

Avoid subclasses that change expected behavior.

---

## 5. I — Interface Segregation Principle (ISP)

### 📌 Definition

Clients should not be forced to depend on interfaces they do not use.

👉 Prefer **small, specific interfaces** over large ones.

### ❌ Bad Example

```dart
abstract class Worker {
  void work();
  void eat();
}
```

### ✅ Good Example

```dart
abstract class Workable {
  void work();
}

abstract class Eatable {
  void eat();
}
```

---

## 6. D — Dependency Inversion Principle (DIP)

### 📌 Definition

High-level modules should not depend on low-level modules. Both should depend on **abstractions**.

👉 Depend on **interfaces**, not concrete implementations.

### Example

```dart
// Abstraction
abstract class Engine {
  void start();
}

// Low-level module: Petrol Engine
class PetrolEngine implements Engine {
  @override
  void start() {
    print("Petrol engine starting...");
  }
}

// Low-level module: Electric Engine
class ElectricEngine implements Engine {
  @override
  void start() {
    print("Electric engine starting silently...");
  }
}

// High-level module: Car
class Car {
  final Engine engine;

  Car(this.engine);

  void startCar() {
    print("Car is starting:");
    engine.start();
  }
}

```

---

## 7. Summary Table

| Principle | Meaning                       |
| --------- | ----------------------------- |
| S         | One class, one responsibility |
| O         | Extend without modifying      |
| L         | Subclasses replace parents    |
| I         | Small, specific interfaces    |
| D         | Depend on abstractions        |

---

## 8. SOLID in Flutter

SOLID principles are commonly applied in Flutter using:

* MVVM / Clean Architecture
* Repository pattern

---

## 9. Conclusion

The SOLID principles are essential for writing **high-quality object-oriented code**. Applying them leads to:

* Cleaner architecture
* Easier testing
* Better scalability

Understanding SOLID is a **must-have skill** for every professional software developer.


