# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:
      def fun(n):
          if n == 0:
              return
          fun(n // 10)
          print(n % 10, end=' ')
      
      def sum_digits(n):
          if n < 10:
              return n
          return sum_digits(n // 10) + n % 10
      
      num = int(input("Enter a number: "))
      total = sum_digits(num)
      
      if total % 2 != 0:
          num += 1
      fun(num)

## OUTPUT
![image](https://github.com/user-attachments/assets/79c00f95-3d0b-4bc8-9182-b26ab5ad61b0)


## RESULT
Thus, the program to write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input) is verified and executed successfully.
