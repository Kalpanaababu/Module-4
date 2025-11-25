# Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## Algorithm

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

```
Developed By : Kalpanaa Babu T M
Reg No : 212224230112

data=eval(input())
sort=dict(sorted(data.items()))
print("Keys and Values sorted in alphabetical order by the key")
for key, value in sort.items():
    print(f"({key}, {value}) ",end="")
```

## Sample Output

<img width="1267" height="115" alt="image" src="https://github.com/user-attachments/assets/9d45f076-11b5-4411-9bc6-e8dea96eacb5" />

## Result

Thus the output is executed successfully.
