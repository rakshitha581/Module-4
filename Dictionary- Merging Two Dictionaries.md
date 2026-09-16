<img width="856" height="248" alt="image" src="https://github.com/user-attachments/assets/ec2ad124-d5aa-459d-b572-058927b5bfa1" />## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
```

## Output
<img width="856" height="248" alt="image" src="https://github.com/user-attachments/assets/832ca8c2-8509-4fe5-9f30-83be99f2bc6a" />

## Result
Thus the program executed successfully.
