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
```
a = input()
if a==a[::-1]:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output
<img width="916" height="195" alt="Screenshot 2025-10-18 200224" src="https://github.com/user-attachments/assets/d1f0f2df-deaf-4d05-8dea-c1028d1ade19" />

## Result
Thus, the program has been executed successfully.
