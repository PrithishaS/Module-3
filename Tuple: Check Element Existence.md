# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program

# Reg.No: 212222210020
# Name: Prithisha S


t = tuple(map(int, input("Enter tuple elements: ").split()))
x = int(input("Enter element to search: "))

if x in t:
    print("Element exists in the tuple")
else:
    print("Element does not exist in the tuple")

## Output

Enter tuple elements: 1 2 3 4 5
Enter element to search: 3
Element exists in the tuple

## Result
The programs were implemented successfully and the outputs were verified.
