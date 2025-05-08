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
class cse():
    def mech(self,num):
        a=math.pi*num*num
        print(f"Areaof circle: {a:.2f}")
a=int(input()) 
obj=cse() 
obj.mech(a)
```
## Output
![image](https://github.com/user-attachments/assets/118fcc3c-0875-4bf6-968c-ff88033ebc79)

## Result
Thus, the program has been successfully executed.

 
