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
list1 = [5, 10, 20,]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")

~~~

## Output
![WhatsApp Image 2025-10-20 at 15 09 26_aed4cc27](https://github.com/user-attachments/assets/fae84b30-133b-46e7-9d94-417d7317d390)

## Result
Thus , the program has been executed succesfully.
