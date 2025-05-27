# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
~~~
my_list = [10, 20, 30, 40, 50]

index = int(input("Enter an index to access: "))

try:
    print(f"Element at index {index}: {my_list[index]}")
except IndexError:
    print(f"Error: Index {index} is out of range! The list contains only {len(my_list)} elements.")
~~~
## Output
~~~
Enter an index to access: 3
Element at index 3: 40
~~~

## Result
Thus given program is verified successfully.

