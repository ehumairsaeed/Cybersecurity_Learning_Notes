# 🐍 Python Tutorial for Beginners – Full Course Notes

🎥 **Source:** [Apna College YouTube Video](https://www.youtube.com/watch?v=ERCMXc8x7mc&ab_channel=ApnaCollege)  
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

## 🧠 01 – OOP - Part 1

### 🔑 Learnings:
- Bsics of OOPS
- Why we use OOPS
- Class & Object in Python
- _ _INIT_ _ Funtion
- Attributes
- Methods
- Static Methods
- Practical Programs

# Practice Code


### OOPS Part 1


#### Creating class
class Student:
    name="David"

s1=Student()

print(s1.name)

class Car:
    color="Black"
    brand="BMW"

car1=Car()
car2=Car()
car3=Car()
print(car1.color)
print(car2.brand)


#### __INIT__ Funtion

class Student:
    def __init__(self,fullname):
        self.name=fullname

s1=Student("David")
print(s1.name)

s2=Student("Andrew")
print(s2.name)

class Student:
    def __init__(self,name,marks):
        self.name=name
        self.marks=marks

s1=Student("David" , 889)
print(s1.name)
print(s1.marks)

s2=Student("Andrew" , 778 )
print(s2.name)
print(s2.marks)

#### Methods

class Student:
    name="Anonymous"
    def __init__(self, name):
        self.name=name

    def hello(self):
        print("Welcome" , self.name )

s1=Student("David")

print(s1.name)
s1.hello()

#### Practice Program 

class Student:
    def __init__(self,fullname, marksphy,marksch,marksma):
          self.name=fullname
          self.marksphy=marksphy
          self.marksch=marksch
          self.marksma=marksma
    
    def avg(self):
         a=self.marksma
         b=self.marksch
         c=self.marksphy
         
         avg=(a+b+c)/3
         return avg

s1=Student("David" , 98,99,97)
print("The Name of Student is "  , s1.name)
print("Avg of their Numbers is " , s1.avg())

s2=Student("Andrew" , 56,14,36)
print("The Name of Student is "  , s2.name)
print("Avg of their Numbers is " , s2.avg())


#### Pracrice Program

class Bank:

    def __init__(self, acc, bal):
        self.account_no=acc
        self.balance=bal

    def debit(self, amount):
        self.balance-=amount
        print("Rs." , amount, "Was Debited")
        print("Remaining Balance is " , self.total())
    
    def credit(self, amount):
        self.balance+=amount
        print("Rs." , amount, "Was Credited")
        print("Remaining Balance is " , self.total())

    def total(self):
        return self.balance
    
acc1=Bank(10024542,100000)
acc1.debit(1050)
acc1.credit(50000)
acc1.debit(19536)