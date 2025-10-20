## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
~~~
dict1 = eval(input())
dict2 = eval(input())
def merge(d1, d2):
    # Merge using unpacking operator (**)
    merged_dict = {**d1, **d2}
    return merged_dict
result = merge(dict1, dict2)
print(result)


~~~

## Output
<img width="1050" height="251" alt="Screenshot 2025-10-20 152122" src="https://github.com/user-attachments/assets/087d406c-6d4b-47af-a825-e3f03f80f01b" /><img width="676" height="251" alt="Screenshot 2025-10-20 152138" src="https://github.com/user-attachments/assets/a84c5b9d-3998-4ef0-a952-d74b7616770e" />


## Result
Thus , the program has been executed succesfully.
