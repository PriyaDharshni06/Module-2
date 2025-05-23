## Loops in Python: Palindrome Number Checker

## 🎯 Aim

To wite a python program to check whether the given number is palindrome or not.


## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `count` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `count = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `count` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
``` pyhton
num=int(input())
temp = num
count =0
while num>0:
    digit =num%10
    count= count*10+digit
    num//=10
if temp== count:
    print("The given number {} is a Palindrome".format(temp))
else:
    print("The given number {} is not a palindrome".format(temp))

```
## Output
![image](https://github.com/user-attachments/assets/22de3a79-e3f0-49d3-be73-abf300a65928)

## Result
Thus python program to check whether the given number is palindrome or not is executed successfully.
