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
        c = math.pi * r**2
        print(f"Area of circle: {c:.2f}")

r = int(input("Enter radius: "))
ci = cse() 
ci.mech(r)

```

## Output

![440260097-8c85a45c-1b4e-4130-99d3-8540084e3ed7](https://github.com/user-attachments/assets/e1d71694-d12a-4161-982f-7ead2e73c781)

## Result

Thus the program that calculates the **area of a circle** based on the radius provided by the user is executed successfully.

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
dict1 = {'Ten': 10, 'Twenty': 20, 'Thirty': 30}
dict2 = {'Thirty': 30, 'Fourty': 40, 'Fifty': 50}

def merge(dict1, dict2):
    res = {**dict1, **dict2}
    return res

dict3 = merge(dict1, dict2)
print(dict3)

```

## Output

![image](https://github.com/user-attachments/assets/11bf89e6-58ae-42c9-b151-39b83741ab95)

## Result

Thus the program that merges **two dictionaries** and combines their key-value pairs is executed successfully.

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


```
d={2:56,1:2,5:12,4:24,6:18,3:323}
l=[]
for i in d:
    l.append(i)
l.sort()
print("Keys and Values sorted in alphabetical order by the key")
for i in l:
    print(tuple([i,d[i]]),end=" ")

```

## Sample Output

![image](https://github.com/user-attachments/assets/b1d7cc6d-72a0-473f-adea-59436601c4bb)

## Result

Thus the program that sorts a dictionary's Keys and Values in alphabetical order is executed successfully.
