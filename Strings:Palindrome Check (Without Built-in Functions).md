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
str = "google"

if str == str[::-1]:
    print("The given string of character is a palindrome")
else:
    print("The given string of character is not a palindrome")
```

   
## Output
<img width="1917" height="497" alt="image" src="https://github.com/user-attachments/assets/14191358-eaec-4f58-9a59-abb4d5459e3b" />

## Result
Thus, The Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions was executed successfully.
