## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dic1=eval(input())
dic2=eval(input())
dic2.update(dic1)
print(dic2)
```
## Output
![Screenshot 2025-06-01 214615](https://github.com/user-attachments/assets/593dbab5-65c0-4e25-9fc1-df929d0d3c39)
![Screenshot 2025-06-01 214625](https://github.com/user-attachments/assets/9a3ae79f-ce20-4e12-a00b-7cac0b1c3954)

## Result
Thus the program has been successfully executed.
