# 🐍 Python Tutorial for Beginners – Full Course Notes

🎥 **Source:** Apna College  
🧑‍💻 **Umair Saeed**  
📅 **Started:** April 2025  
📘 **Purpose:** Build strong Python skills for Cybersecurity, Automation & Ethical Hacking

---

## 📑 Course Chapters

1. Introduction
2. Variables and Data Types
3. Strings and Conditional Statements
4. Lists and Tuples
5. Dictionary and Set
6. Loops
7. Functions and Recursion
8. File Input and Output
9. OOP - Part 1
10. OOP - Part 2
11. Mini Project

---

## 🧠 01 – OOP - Part 2

### 🔑 Learnings:
- DEL Keyword
- Private Attibutes
- Inheritence
- Supper Method
- Class Method
- Property Decorator
- Polymorphizm
- Practice Programs


# Practice Code

## OOPS PART 2

class Student:

    def __init__(self,name):
        self.name=name

    def prinn(self):

        return print(self.name)

s1=Student("David")
s1.prinn()

#### USING DEL KEYWORD

class Student:

    def __init__(self,name):
        self.name=name

    def prinn(self):

        return print(self.name)
s1=Student("David")
s1.prinn()
s2=Student("ANDREW")
s2.prinn()

del s1.name
s1.prinn()
s2.prinn()
del s2.name
s2.prinn()

#### PRIVATE ATRIBUTES

class ACC:

    def __init__(self,acc_no, acc_pass):
        self.acc_no=acc_no
        self.__acc_pass=acc_pass

    def reset_pass(self):

        return print(self.__acc_pass)
    
acc1=ACC("123456789" , "absgnhfj")
print(acc1.acc_no)
acc1.reset_pass()

#### INHERITENCE


class A:
    vara="Welcome to class A"

class B:
    varb="Welcome to class B"

class C(A,B):
    varc="Welcome to class C"

c1=C()

print(c1.vara)
print(c1.varb)
print(c1.varc)

#### Super Method

class Car:
    def __init__(self, type):
        self.type=type

    @staticmethod
    def start():
        print("car Started")
    
    @staticmethod
    def stop():
        print("car Stoped")

class Toyotacar(Car):
    def __init__(self, name,  type):
        self.name=name
        super().start()
        super().stop()
        super().__init__(type)


car1=Toyotacar("Hilux" ,"Petrol" )
print(car1.name)
print(car1.type)



#### Class Method


class Person:
    name="anonymous"
    @classmethod
    def changename(cls, name):
        cls.name=name

p1=Person()
p1.changename("David")
print(p1.name)
print(Person.name)

#### Property 

class Student:
    name=""
    def __init__(self, chy, comp,math,bio):
        self.chy=chy
        self.comp=comp
        self.math=math
        self.bio=bio

        self.percen= str((self.bio+self.chy+self.comp+self.math) / 4) + "%"

s1=Student(78,69,56,10)
print(s1.percen)

#### Practice Program

class Circle:
    def __init__(self, radius):
        self.radius=radius

    def area(self):
        return (22/7) * self.radius ** 2 
    def paremeter(self):
        return 2 * (22/7) * self.radius
    
s1=Circle(21)

print(s1.area())
print(s1.paremeter())


#### Practice Program

class Employe:
    def __init__(self,role,department,salary):
        self.role=role
        self.department=department
        self.salary=salary

    def show_Details(self):
        print("Role = ", self.role)
        print("Department = ", self.department)
        print("Salary = ", self.salary)

class Engenier(Employe):
    def __init__(self, name,age):
        self.name=name
        self.age=age
        super().__init__("ENG", "IT" ,9665656)
        


eng1=Engenier("David" ,96)
eng1.show_Details()


#### Practice Program 

class Order:
    def __init__(self, item, price):
        self.item=item
        self.price=price

    def __gt__(self,ord2):
        return self.price > ord2.price
    
ord1=Order("ghdf" , 12)
ord2=Order("jhjfh" , 885)

print(ord1 < ord2)




