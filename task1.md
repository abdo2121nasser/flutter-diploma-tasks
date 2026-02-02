

# 📝 Task 1
<br>
<br>

## 📌 Question 1

> *Create a variable called age and assign your age to it.*
---

## 💻 Code / Solution

```text
void main() {
 int age;
 age = 22;
}
```

>**screenshot of code:**<br>
<img width="474" height="302" alt="image" src="https://github.com/user-attachments/assets/ea2a9c52-0afe-41e1-9842-a84fbe3b1f84" />
---

## 📌 Question 2

> *Create two variables: firstName and lastName, then print your full name.*
---

## 💻 Code / Solution

```text
void main() {
 String firstName='Abdulrahman', lastName = 'Nasser';
 print(firstName+' '+lastName);
}
```

>**screenshot of code:**<br>
<img width="986" height="422" alt="image" src="https://github.com/user-attachments/assets/0ffa464b-f594-4e25-9bbd-0d577b683aaf" />
---

## 📌 Question 3

> *Create a double variable named heightInMeters and assign your height.*
---

## 💻 Code / Solution

```text
void main() {
 double heightMeter = 1.7;
 print(heigthMeter);
}
```

>**screenshot of code:**<br>
<img width="747" height="371" alt="image" src="https://github.com/user-attachments/assets/dfa27863-4e3f-4648-9e25-98e595cfd6bf" />

---

## 📌 Question 4

> *Create a bool variable named isStudent and assign it true or false.*
---

## 💻 Code / Solution

```text
void main() {
 bool isStudent;
 isStudent = true;
 print(isStudent);
}
```

>**screenshot of code:**<br>
<img width="782" height="371" alt="image" src="https://github.com/user-attachments/assets/fad93900-a2c6-4817-b977-e59ab51fe4f2" />

---

## 📌 Question 3

> *Create two variables: x = 12 and y = 4. Print the result of:*
* x + y
* x - y
* x * y
* x / y
* x % y
---

## 💻 Code / Solution

```text
void main() {
print(x+y);
print(x-y);
print(x*y);
print(x/y);
print(x%y);
}
```

>**screenshot of code:**<br>
<img width="825" height="504" alt="image" src="https://github.com/user-attachments/assets/e918fe56-77b3-486c-9bf5-259adfc369b2" />

---
## 📌 Question 6

> *If you have a variable radius = 5, write a formula to calculate the area of a circle using pi = 3.14.*
---

## 💻 Code / Solution

```text
void main() {
int radius = 5;
double pi=3.14;
print(radius*radius*pi);
}
```

>**screenshot of code:**<br>
<img width="785" height="364" alt="image" src="https://github.com/user-attachments/assets/d5f084eb-37c9-439e-90c9-cd884e1d93a8" />
---
## 📌 Question 7

> *Create a variable minutes = 120. Convert it into hours and print the result.*

---

## 💻 Code / Solution

```text
void main() {
  double minute = 120;
  double hour = minute /60;
  print(hour);
}
```

>**screenshot of code:**<br>
<img width="796" height="367" alt="image" src="https://github.com/user-attachments/assets/786ea70d-4466-4c0f-ae16-abf0c03cf9d8" />

---
## 📌 Question 8,9,10

> *Predict the output of the following, then write code to check:*
* int result1 = 2 + 3 * 4;
* int result2 = (2 + 3) * 4;
* int result3 = 10 - 2 * 3 + 1;

---

## 💻 Code / Solution

```text
void main() {

  //first int result1 = 2 + 3 * 4;
//we will start with the multiplication -> 3 * 4 = 12
 //then the addition with the result -> 2 + 12 = 14

  //second int result2 = (2 + 3) * 4;
//we will start with the processes in brackets -> ( 2 + 3 ) = 5
//then we do multiplication with the result -> 5 * 4 = 20

  //third result3 = 10 - 2 * 3 + 1;
//we will start with the multiplication -> 2 * 3 = 6
//then we will do the operations form left to right cause they have same priority
//so we will subtract the result  -> 10 - 6 = 4
//then we will do addition to the result -> 4 + 1 = 5
}
```

## 📌 Question 11

> *Dart Program to Check if a Number is Positive or Negative or Zero.*

---

## 💻 Code / Solution

```text
void main() {
  int value = 5;
  if(value==0){
    print('the value is zero');

  }
  else if(value > 0){
    print('the value is positive');
  }
  else{
    print('the value is negative');
  }
}
```

>**screenshot of code:**<br>
<img width="954" height="635" alt="image" src="https://github.com/user-attachments/assets/7d44debc-f949-4112-85b1-084e73918900" />

---

## 📌 Question 12

> *Dart Program to Check if a Number is Even or Odd.*

---

## 💻 Code / Solution

```text
void main() {
 if(value %2 == 0){
    print('the value is even');
  }
  else{
    print('the value is odd');
  }
}
```

>**screenshot of code:**<br>
<img width="859" height="477" alt="image" src="https://github.com/user-attachments/assets/93f4c8ff-dde5-455b-9f88-a41cdf7d0e36" />

---


## 📌 Question 13

> *Program to find largest and smallest element of 3 values.*

---

## 💻 Code / Solution

```text
void main() {
 int a = 9, b = 4, c = 5;
  int largest, smallest;
  if (a >= b && a >= c) {
    largest = a;
  } else if (b >= a && b >= c) {
    largest = b;
  } else {
    largest = c;
  }
  if (a <= b && a <= c) {
    smallest = a;
  } else if (b <= a && b <= c) {
    smallest = b;
  } else {
    smallest = c;
  }
  print("Largest number: $largest");
  print("Smallest number: $smallest");
}
```

>**screenshot of code:**<br>
<img width="937" height="793" alt="image" src="https://github.com/user-attachments/assets/1df5de95-483f-4d2e-ae2e-c83e223eea07" />




