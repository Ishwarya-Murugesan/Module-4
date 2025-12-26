# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

```
import math

class cse:
    def mech(self, r):
        area = math.pi * r * r
        print("Area of the circle:", area)

radius = float(input("Enter the radius of the circle: "))
obj = cse()
obj.mech(radius)
```

## Output
<img width="1920" height="1080" alt="Screenshot (126)" src="https://github.com/user-attachments/assets/a7f6e2eb-ec82-4d74-8846-a6bb36872751" />

## Result
Thus, the program is executed successfully.
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
def merge(dict1, dict2):
    merged = {**dict1, **dict2}
    return merged

dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'d': 4, 'e': 5, 'a': 6}

result = merge(dict1, dict2)
print("Merged dictionary:", result)
```

## Output
<img width="1920" height="1080" alt="Screenshot (127)" src="https://github.com/user-attachments/assets/14a9f3d9-b1e5-42ee-8907-c698cfbbf5c4" />

## Result
Thus, the program is executed successfully.
