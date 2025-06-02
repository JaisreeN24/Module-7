# 📐 Taylor Series Using Recursion in Python

## 🎯 AIM:
To write a Python program to evaluate a **Taylor Series** using **recursion**, where values of `x` and `n` are taken from the user.

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `x` and `n`
3. Get values for `x` and `n` from the user
4. Define a recursive function `series(x, n)`
   - **Base case:** If `n == 0`, return 1
   - **Recursive case:** Return `x**n / n + series(x, n-1)`
5. Print the result
6. **Stop**

## 💻 PROGRAM:

      x=int(input())
      n=int(input())
      def fun(x,n):
          if n==1:
              return x
          else:
              return x**n+fun(x,n-1)
      print(1+fun(x,n))

## OUTPUT
![image](https://github.com/user-attachments/assets/d81380d4-ca7b-485b-8d90-6d22f082313f)

## RESULT
Thus, the program to evaluate a **Taylor Series** using **recursion**, where values of `x` and `n` are taken from the user is executed and verified successfully.
