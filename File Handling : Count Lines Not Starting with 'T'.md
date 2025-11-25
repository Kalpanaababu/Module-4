# File Handling in Python: Count Lines Not Starting with 'T'

## Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## Program

```
Developed By : Kalpanaa Babu T M
Reg No : 212224230112

count_lines.py

f = open("story.txt", "r")
count = 0
for line in f:
    if not line.startswith('T'):
        count += 1
print(count)
f.close()

story.txt

Today the sun rose behind the hills.
The river flowed silently through the valley.
Mountains were standing tall and proud.
Time moves fast when you are focused.
A gentle breeze passed through the trees.
Technology is transforming every industry.
Creativity fuels innovation and growth.
Talent without discipline delivers inconsistent outcomes.
Dreams demand execution, not intention.
Teamwork accelerates operational efficiency.
```

## Output

<img width="1322" height="125" alt="image" src="https://github.com/user-attachments/assets/cb85de5f-df6d-4886-8079-d4f102e10072" />

## Result

Thus the output is executed successfully.
