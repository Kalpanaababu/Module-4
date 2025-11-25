## Dictionary Operations in Python: Merging Two Dictionaries

## Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## Program

```
Developed By : Kalpanaa Babu T M
Reg No : 212224230112

dict1=eval(input())
dict2=eval(input())
dict1.update(dict2)
print(dict1)
```

## Output

<img width="1137" height="249" alt="image" src="https://github.com/user-attachments/assets/e8468840-957b-46e4-b404-a2f2313a1a8f" />

## Result

Thus the output is executed successfully.
