# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
~~~

my_dict = {"apple": 3, "banana": 1, "cherry": 5, "date": 2}

sorted_keys = dict(sorted(my_dict.items()))

sorted_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

print("\nDictionary sorted by keys:")
print(sorted_keys)

print("\nDictionary sorted by values:")
print(sorted_values)
~~~
## Sample Output
~~~
Dictionary sorted by keys:
{'apple': 3, 'banana': 1, 'cherry': 5, 'date': 2}

Dictionary sorted by values:
{'banana': 1, 'date': 2, 'apple': 3, 'cherry': 5}
~~~

## Result
Thus given program is verified successfully

