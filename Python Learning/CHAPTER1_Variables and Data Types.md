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

## 🧠 02 – Variables and Data Types

### 🔑 Learnings:
- Installing Python on windows and MacOS
- Downloading and installing VS Code on Windows and MacOS
- Basics of python 
- Variables
- Data Types
- Expresion Execution
- Input in python 
- Conditional Statements
- Types of Operators
- PROGRAM TO INPUT 2 NUMBERS AND PRINT THEIR SUM 
- Program SUM OF TWO NUMBER OR DIFFER OF TWO NUMBERS 
- Program to find the area of square
- Program to print the average of two float values
- True False Program




# Practice code:


 print("Hello World")
 print("My name is umair." , "My name is umair." , "My name is umair.")
 print(233369)

#### variables 

 name = "Umair"
 age = 20
 hight= 30.9
 new = False
 aa = None

 print("My name is :" , name)
 print("My age is :" , age)
 print("My hight is :" , hight)
 print("My name is :" , name , "AND  " "My age is :", age , "AND  " "My hight is :" , hight)

#### Check DATA TYPE
 print(type(name))
 print(type(age))
 print(type(hight))
 print(type(new))
 print(type(aa))

#### Program SUM OF TWO NUMBER OR DIFFER OF TWO NUMBERS 

 a=1000
 b=500
 differ=a-b
 print(differ)

#### INPUT INTO VARIABLE

 name = input("Name :")
 age = int(input("Age :"))
 height = float(input("Height :"))

 print("Your Name is :" , name)
 print("Your Age is :" , age)
 print("Your Height is :" , height)




#### Conditional Statement 

 light = input("Whats the Colour of Light :")
 if(light == "red" or light=="RED" or light=="Red"):
     print("stop")
 elif(light == "yellow" or light=="YELLOW" or light=="Yellow"):
     print("Look Around")
 elif(light == "green" or light=="GREEN" or light=="Green"):
     print("Go Fast")
 else:
     print("Light is Broken")

#### PROGRAM TO INPUT 2 NUMBERS AND PRINT THEIR SUM 

 num1 = int(input("Enter Your First Num :"))
 num2 = int(input("Enter Your Second Num :"))

 sum = num1 + num2

 print("The Sum of the Two Numbers is this :" , sum)


#### Program to find the area of square

 side = float(input("ENTER THE VALUE OF SIDE :"))

 area = side * side

 print("THE AREA OF THE SQUARE IS :" , area)

#### Program to print the average of two float values

 num1 = float(input("ENTER THE NUMBER :"))
 num2 = float(input("ENTER THE NUMBER :"))

 avg= (num1+num2)/2
 print("THATS THE AVG OF TWO VALUES :" , avg)


#### TRUE FALSE PROGRAM 

 num1 = int(input("ENTER FIRST NUM :"))
 num2 = int(input("ENTER Second NUM :"))

 if(num1>=num2):
     print("TRUE")
 else:
     print("FALSE")

