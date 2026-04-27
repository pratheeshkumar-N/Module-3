# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```py
a = input()
s = a[::-1]
if a == s:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output

<img width="900" height="246" alt="444879386-e8566790-cbd2-48f9-9e28-09125e0e8a09" src="https://github.com/user-attachments/assets/ac293c8a-1d88-4124-843d-197219081e6e" />

## Result
Thus, the program executed successfully.
