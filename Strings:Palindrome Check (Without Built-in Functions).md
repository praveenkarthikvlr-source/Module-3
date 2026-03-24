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

def remove(a,n):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
a=input()
n=int(input())
remove(a,n)
## Output

<img width="685" height="142" alt="image" src="https://github.com/user-attachments/assets/92167bd1-5a45-465a-94e0-57b1f6eafb4d" />


## Result

<img width="685" height="142" alt="image" src="https://github.com/user-attachments/assets/e157f3d5-198e-4131-81d6-67c10238eff0" />
