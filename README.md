# Object Oriented Programming

Writing clean code is a key component of OOP.
The biggest advantage of structuring your software into straightforward, 
reusable bits of code—basically, cleaner code—comes from creating your code in an object-oriented manner.



## Sample Code

```
class Employee:
    def __init__(self, name, age, salary, position, department, marital_status):
        self.name = name
        self.age = age
        self.salary = salary
        self.position = position
        self.department = department
        self.marital_status = marital_status
        
    def add_age(self):
        self.age += 1
        
    def get_age(self):
        return "Age is {}".format(self.age)
```


## Pillars of OOP 

- Encapsulation
- Iheritance
- Polymorphism
- Abstraction