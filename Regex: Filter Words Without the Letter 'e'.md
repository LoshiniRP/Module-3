# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
result = []
for i in items:
    if not re.search('e', i):
        result.append(i)
print(result)
```
## Output
<img width="435" height="159" alt="Screenshot 2025-10-18 195748" src="https://github.com/user-attachments/assets/ac708e8f-8190-4c74-8801-f9fcd61008c2" />

## Result
Thus, the program has been executed successfully.
