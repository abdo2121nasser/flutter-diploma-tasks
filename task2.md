

# 📝 Task 2
<br>
<br>

## 📌 Question 1

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

## 📌 Question 2

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

## 📌 Question 3

> *Dart Program to Calculate the Sum of first 100 Natural Numbers.*
---

## 💻 Code / Solution

```text
void main() {
 int sum=0;
 for(int i =0;i<=100;i++){
   sum+=i;
 }
 print(sum);
}
```

>**screenshot of code:**<br>
<img width="524" height="368" alt="image" src="https://github.com/user-attachments/assets/6cb66769-0dd3-4d18-affb-452a7906ae45" />

---

## 📌 Question 4

> *Dart Program to Make a Simple Calculator Using switch...case.*
---

## 💻 Code / Solution

```text
void main() {
   int num1=10,num2=12;
   String operation = '+';
   switch(operation){
     case '+':
       print(num1+num2);
       case '-':
       print(num1-num2);
       case '*':
       print(num1*num2);
       case '/':
       print(num1/num2);
   }
}
```

>**screenshot of code:**<br>
<img width="572" height="533" alt="image" src="https://github.com/user-attachments/assets/77805a1f-2efc-4fe8-afc7-2ce320fbf2ba" />

---

## 📌 Question 5

> Program to find largest and smallest element of 3 values.*
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

---
## 📌 Question 6

> *Dart Program to display even numbers from 1 to n numbers.*
---

## 💻 Code / Solution

```text
void main() {
  int n = 100;
  for (int i = 0; i <= n; i++) {
    if (i % 2 == 0) {
      print(i);
    }
  }
}
```

>**screenshot of code:**<br>
<img width="492" height="817" alt="image" src="https://github.com/user-attachments/assets/225b1724-6efc-445a-b660-4b337dc15d0a" />

---

## 📌 Question 7

> *Dart Program to find Factorial using loops.*
### Test Data
 * Input the number : 5
 * Expected Output: 120

---

## 💻 Code / Solution

```text
void main() {
  int factorial = 1;
  int n = 5;
  for (int i = 1; i <= n; i++) {
    factorial *= i;
  }
  print(factorial);
}
```

>**screenshot of code:**<br>
<img width="551" height="423" alt="image" src="https://github.com/user-attachments/assets/5af2109f-e0a5-4f3e-b82d-74b8f4ce9f54" />

---




