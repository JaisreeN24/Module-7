# 📐 Taylor Series:sinh(x) Evaluation using Recursion in Python

## 🎯 AIM:
To write a Python program to evaluate the value of **sinh(x)** for **n terms** using recursion.

---

## 🧠 ALGORITHM:

1. **Start**
2. Read input for variable `x` (angle or number)
3. Read input for variable `n` (number of terms)
4. Define a function `fact(n)`:
   - If `n <= 1`, return 1
   - Else, return `n * fact(n - 1)` (recursive factorial)
5. Define a function `sinh(x, n)`:
   - If `n == 0`, return `x`
   - Else, return `(pow(x, 2*n + 1) / fact(2*n + 1)) + sinh(x, n - 1)`
6. Call the `sinh(x, n)` function and print the result
7. **Stop**

---

## 💻 PROGRAM:
      def fact(n):
          return 1 if n <= 1 else n * fact(n - 1)
      
      def sinh(x, n):
          return x if n == 0 else (x**(2*n + 1)) / fact(2*n + 1) + sinh(x, n - 1)
      
      x = float(input())
      n = int(input())
      result = sinh(x, n - 1)
      print(f"sinh({x}) with {n} terms: {result}")

## OUTPUT
![image](https://github.com/user-attachments/assets/a6b9700b-164a-4945-80ba-acd4dc544ea6)

## RESULT
Thus, the program to  evaluate the value of **sinh(x)** for **n terms** using recursion is executed and verified successfully.
