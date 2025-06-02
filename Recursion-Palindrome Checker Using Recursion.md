# 🔁 Recursion:Palindrome Checker Using Recursion in Python

## 🎯 AIM:
To write a Python program to check whether a given string is a **palindrome** using **recursion**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `is_palindrome(word)`
   - **Base Case:** If the string length is less than 1, return `True`
   - **Recursive Case:** If the first and last characters match, call the function recursively on the substring without first and last characters
   - Else, return `False`
3. Get input from the user
4. Call the recursive function
5. Print whether the string is a palindrome
6. **Stop**

---

## 💻 PROGRAM:
      def is_palindrome(word):
          if len(word) <= 1:
              return True
          if word[0] != word[-1]:
              return False
          return is_palindrome(word[1:-1])
      
      word = input("Enter a word: ").lower()
      if is_palindrome(word):
          print("Palindrome")
      else:
          print("Not a palindrome")

## OUTPUT
![image](https://github.com/user-attachments/assets/8a1eea49-94bc-41a7-92c1-7dd02d11e643)

## RESULT
Thus the program to check whether a given string is a **palindrome** using **recursion** is executed and verified successfully.
