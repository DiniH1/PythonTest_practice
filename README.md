# Test practice 
### Declare a function called user_name that takes one arg as a str and return the name
```
name = "dini"
def user_name(name):
    return name
print(user_name(name))
```
### Declare a list with num 1-5 and iterate through the list and display list
```
list = [1.,2,3,4,5]
for num in list:
    print(num)
```
### What is the difference between a list and a tuple
- A list is mutable
- A tuple is immutable

### Can we add an element to a list 
- Yes
### Can we add an element to a tuple
- Yes
### Can the element of a tuple be different types 
- Yes

### Create a dict with key, val pairs first name last name
```
dict = {"first_name":"Dini", "last_name": "Hassan"}
dict["course"] = "Devops"
print(dict)
```

### Create a class called `student` init the class and create an object of that of the class
```
class Student():
    def __init__(self):

    def name(self):
        return self.name()

devops_student = Student("Dini")
```

### create two functions that take two args each func 1 called add_values func 2 subtract_values
```
def add_values(x,y):
     return x + y
def subtract_values(x,y):
     return x -y
```
### Declare a dict with 3 shopping items with cost eggs £1.20 milk £2.30 bread £1.00 write a fun that returns the total value
```
shopping = {"eggs":"£1.20", "milk":"£2.30", "bread":"£1.00"}
def total_value(a,b,c):
    return shopping["eggs"] + shopping["milk"] + shopping["bread"]
print(total_value())
```
### Prompt the user to enter an int declare a func that checks if the num is odd or even display back with num entered is odd or even
```
num = int(input("Pick a number "))

def odd_checker(num):
    if num % 2 == 0:
        return f"The number {num} is even"
    else:
        return f"The number {num} is odd"
print(odd_checker(num))
```
### Declare a tuple 3 vals of your choice iterate through the tuple display the vals
```
my_tuple = (1,2,3)
for num in my_tuple:
    print(num)
```

### Create a class called student with one method called student data that returns student name create a class called devops student inherit student class inside  student class
```
name = "Dini"
class Student():
    def student_data(self, name):
        return name

class Devops_student(Student):
    def __init__(self):
        pass
sd = Devops_student()
print(sd.student_data(name))
```
### Declare a variable called city declare a method that takes city as an arg val of city is london
```
city = "London"
def city_checker(cityname):
    if cityname == "London":
        return True
    else:
        return False
print(city_checker(city))
```
