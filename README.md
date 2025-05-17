# 19CS301-Module-6
EX: 6.1   POLYMORPHISM

### AIM: 
To Create two specific classes- Beans and Mango. Along with that, create a generic function that tells us the type and color of the object we pass. Mind you, since we have passed only “obj” through it, this obj can be any object.


### ALGORITHM:

Step1: create class Beans and def a function type and color

Step 2: create a class Mango and def a function type and color

Step3: def a function func

Step 4: call the objects and execute the program

### PROGRAM:
```
class Beans ():
    def type(self):   
          print("Vegetable")
    def color(self):
          print("Green")
class Mango:
   def type(self):
          print("Fruit")
   def color(self):
         print("Yellow")
   def func(obj):
         obj.type()
         obj.color()
         obj_beans = Beans()
         obj_mango = Mango()
         func(obj_beans)
         func(obj_mango)
```
### OUTPUT:
![image](https://github.com/gokulkrishnan2005/19CS301-Module-6/blob/main/20.png)


### RESULT: Thus, the program has been successfully executed.

EXP.No: 6.b OPERATOR OVERLOADING

### AIM:
write a python program to overload less than operator
###ALGORITHM:

Step1 :create class A and def init	 

Step2: def it	with a condition if self.a < o.a 

Step 3: call the function and execute the program.
### PROGRAM:
```
class A :
     def     init (self,a):
             self.a=a
     def     lt (self,o):
              if self.a < o.a :
                   return "ob1 is less than ob2"
              else:
                   return "ob2 is less than ob1"
ob1 = A(2)
ob2 = A(3)
print(ob1<ob2)
```
###OUTPUT:

![image](https://github.com/gokulkrishnan2005/19CS301-Module-6/blob/main/21.png)



###RESULT: 
Thus, the program has been successfully executed.
EX: 6.3 ABSTRACT CLASS METHOD

### AIM: To Create the abstract method calculate_area which is of the abstract class 'Shape'

### ALGORITHM:

Step1:Get input from the user

Step2:put class function to define the function using self

Step3:By using the function to find the area of the rectangle and circle Step4:Execute the program.

### PROGRAM:
```from abc import ABC
class Shape(ABC):
            def calculate_area(self):
                Pass
class Rectangle(Shape):
               length = 5
               breadth =3
               def calculate_area(self):
                   print("Area of a rectangle:",self.length * self.breadth)
class Circle(Shape):
             radius = 4
             def calculate_area(self):
                     print("Area of a circle:",3.14 * self.radius * self.radius)
a=Rectangle()
b=Circle()
a.calculate_area()
b.calculate_area()
```
### OUTPUT:
![image](https://github.com/gokulkrishnan2005/19CS301-Module-6/blob/main/22.png)


### RESULT: Thus, the program has been successfully executed.

EXP.No: 6.4     ENCAPSULATION
### AIM: To Implement Encapsulation using concepts to access the private variables in ABC class. 

###ALGORITHM: 

Define class ABC with a private variable __a.

Create a constructor __init__() to initialize __a = 5.

Define method fun() to print a public message.

Define method fun1() to print a private message and the value of __a.

Create object x of class ABC.

Call x.fun() to execute the public method.

Call x.fun1() to execute the method accessing the private variable.
###PROGRAM:
```
class ABC:
    def __init__(self):
        self.__a=5
    def fun (self):
        print("I am public class method")
    def fun1(self):
        print("I am private class method")
        print(self.__a)
x=ABC()
x.fun()
x.fun1()
```
### OUTPUT:
 
![image](https://github.com/gokulkrishnan2005/19CS301-Module-6/blob/main/23.png)

 

### RESULT:

Thus, the program has been successfully executed

EXP.No: 6.b OPERATOR OVERLOADING

### AIM: To Create the abstract method calculate_area which is of the abstract class 'Shape'

### ALGORITHM:

Step1:Get input from the user

Step2:put class function to define the function using self

Step3:By using the function to find the area of the rectangle and circle Step4:Execute the program.

### PROGRAM:
```from abc import ABC
class Shape(ABC):
            def calculate_area(self):
                Pass
class Rectangle(Shape):
               length = 5
               breadth =3
               def calculate_area(self):
                   print("Area of a rectangle:",self.length * self.breadth)
class Circle(Shape):
             radius = 4
             def calculate_area(self):
                     print("Area of a circle:",3.14 * self.radius * self.radius)
a=Rectangle()
b=Circle()
a.calculate_area()
b.calculate_area()
```
### OUTPUT:
![image](https://github.com/gokulkrishnan2005/19CS301-Module-6/blob/main/22.png)


### RESULT: Thus, the program has been successfully executed.





