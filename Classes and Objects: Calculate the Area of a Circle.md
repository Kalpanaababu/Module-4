# Classes and Objects in Python: Calculate the Area of a Circle

## Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## Program

```
Developed By : Kalpanaa Babu T M
Reg No : 212224230112

import math

class pen:
    def stationary(self, radius):
        area = math.pi * radius * radius
        return area


r = float(input())
obj = pen()
result = obj.stationary(r)
print(f"Area of circle: {result:.2f}")
```

## Output

<img width="637" height="209" alt="image" src="https://github.com/user-attachments/assets/32a40f75-b5cd-4875-b033-75ca79bd4966" />

## Result

Thus the output is executed successfully.
