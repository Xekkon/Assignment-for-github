# Assignment-for-github
README, assignment 3 solved 

#Q1
product = lambda x,y : x*y
print("Output:",product(5,6))

#Q2
import math
def circle_area(radius):
 area = math.pi * radius**2
 return area
radius = 10
area = circle_area(radius)
print("Output: ",area)

#Q3
def calculate(num1,num2,operation):
 if operation == 'a':
 return num1 + num2
 elif operation == 's':
 return num1 - num2
 elif operation == 'm':
 return num1 * num2
 elif operation == 'd':
 if num2 != 0:
 return num1 / num2
 else:
 return "Error: Division by zero"
 else:
 return "Error: Invalid operation"
result = calculate(2,5,'d')
print("Output: ",result)


#Q4
class Rectangle:
 def __init__(self,length,width):
 self.length = length
 self.width = width 
 def area(self):
 return self.length * self.width
r = Rectangle(5,10)
print("Output:",r.area())

#Q5
class Shape:
 def __init__(self, name, length):
 self.name = name
 self.length = length
 def area(self):
 return 0
class Square(Shape):
 def __init__(self, name, length):
 Shape.__init__(self, name, length)
 def area(self):
 return self.length ** 2
 def describe(self):
 return f"This is a: {self.name}"
s = Square('square', 5)
print("The area is:",s.area())
print(s.describe())


wadkawdkiawprakwarrw
