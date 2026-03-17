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

# Reg.No: 212222210020
# Name: Prithisha S

n = int(input("Enter number of rows: "))

for i in range(n):
    num = 1
    for j in range(n - i):
        print(" ", end="")
    for j in range(i + 1):
        print(num, end=" ")
        num = num * (i - j) // (j + 1)
    print()

## Output
Enter number of rows: 5
     1
    1 1
   1 2 1
  1 3 3 1
 1 4 6 4 1
 
## Result
The programs were implemented successfully and the outputs were verified.

