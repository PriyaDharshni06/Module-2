# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1.Start

2.Read an integer n from the user

3.Repeat for i from 0 to n-1:

4.Repeat for j from i to n-1:

5.Print the value of n followed by a space, staying on the same line

6.Print a newline character after the inner loop

7.End program.


## 🧪 Program
```python
n=int(input())
for i in range(0,n):
    for j in range(i,n):
        print(n,"",end="")
    print()

```
## Sample Output
![image](https://github.com/user-attachments/assets/a1cf7bed-c40b-427d-85d4-fa0c8669b9c0)

## Result
Thus the Python program that generates **Pascal's Triangle** using numbers is executed successfully.
