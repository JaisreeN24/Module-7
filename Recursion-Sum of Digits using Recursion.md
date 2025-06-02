# # 🔁 Recursion:Sum of Digits using Recursion in Python

## 🎯 AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

## 💻 PROGRAM:
      def sum_digits(num):
          if num < 0 or int(num) != num:
              return 0
          elif num == 0:
              return 0
          else:
              return (num % 10) + sum_digits(num//10)
      num= int(input())
      print(sum_digits(num))

## OUTPUT
![image](https://github.com/user-attachments/assets/edef1c2d-9549-4185-b72a-b037245a24c6)

## RESULT
Thus, the program to calculate the **sum of all digits** in a number using **recursion** is executed and verified successfully.
