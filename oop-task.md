

# 📝 OOP Task
<br>
<br>

## 📌 Question 1

> *(Constructor) : Write a class Mobile with three properties
name, color, and prize. The class has one method display which
prints out the values of the three properties. We also have an
object of the class Mobile called mobile. There is also
constructor Mobile which takes all the three properties as
Parameters.*
---

## 💻 Code / Solution
>*each class should be in separated file:*

```text
class Mobile {
  String name, color;
  int prize;
  Mobile({required this.name, required this.color, required this.prize});
  void display() {
    print('name: $name color: $color prize: $prize');
  }
}
```
```text
void main() {
  Mobile mobile = Mobile(name: 'sumsung', color: 'green', prize: 2000);
  mobile.display();
}
```
>**screenshot of code:**<br>
<img width="758" height="234" alt="image" src="https://github.com/user-attachments/assets/8bf3f84b-cfbd-4a0c-abcc-41b4e793eea7" />
<img width="872" height="322" alt="image" src="https://github.com/user-attachments/assets/7665fdf5-6a3b-4862-91f6-9892538dacd1" />

---

## 📌 Question 2

> *(Encapsulation) : Write a class named BankAccount with one
private property _balance. There is one getter balance to read
the value of the property. There are methods deposit )ابداع )and
withdraw (سحب (to update the value of the _balance.*
---

## 💻 Code / Solution

```text
class BankAccount {
  double _balance = 0;
  get balance => _balance;
  void deposit(double amount) {
    if (amount > 0) {
      this._balance += amount;
    } else {
      print('the value is unvalid');
    }
  }
  void withDraw(double amount) {
    if (amount > 0) {
      this._balance -= amount;
    } else {
      print('the value is unvalid');
    }
  }
}
```

>**screenshot of code:**<br>
<img width="505" height="498" alt="image" src="https://github.com/user-attachments/assets/6db344cd-0ba8-4dd4-a4ea-98809f871b7e" />








