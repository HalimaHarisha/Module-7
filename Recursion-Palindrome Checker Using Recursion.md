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

```
l=[]
def SUM(n):
   if n==0:
      return 1
dig=n%10
l.append(dig)
SUM(n//10)
n=int(input())
SUM(n) print(sum(l))
```
## OUTPUT

<img width="268" height="147" alt="image" src="https://github.com/user-attachments/assets/82adb0aa-14e1-4934-b623-ed4520cadbba" />


## RESULT
Program successfully verified.
