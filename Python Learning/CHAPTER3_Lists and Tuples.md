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

## 🧠 04 – Lists and Tuples

### 🔑 Learnings:
- Lists in Python
- Difference B/w mutable and imutable
- List Slicing 
- List Method
- Tuples in Python
- Tuples Slicing
- Tuples Method
- Practice Programs


# Practice code:



#### Data Storing with variables

 marks1=81
 marks2=80
 marks3=85
 marks4=79
 marks5=96

#### Data Storing With list
 marks=[96,78,56,45,73]

 print(marks)

 print(marks[3])

#### Multiple Data Type List

 student=["Umair", 90, "Pakistan"]

 print(student[2])

#### changing value 

 student[2]="Dubai"
 print(student)

#### List Slicing 

 marks=[12,153,1274,214,24567,235,2124,24]

 print(marks[2:6])

#### List Method 

 list=[1,2,35,478,54]
 list.append(96)
 list.sort(reverse=True)
 print(list)


#### Tuples 

 tup=(96,86,456,24,322,47,57,581,24)
 print(tup[3])
 print(type(tup))


#### A program which ask user to input their 3 movies names

 mo1=input("Enter The name of 1st Movie :")
 mo2=input("Enter The name of 2nd Movie :")
 mo3=input("Enter The name of 3rd Movie :")

 movi=[mo1,mo2,mo3]
 print(movi)


#### A Program That check a list contatain Palendrom

 list=[1,2,1]
 list1=list.copy()
 print(list)
 print(list1)
 list1.reverse()
 if(list==list1):
     print("The List is Panlindrome")
 else:
     print("The List is Not a Panlindrome")


#### A program that count the number of students with thw grade A in a tuple

 grade=("A","B","C","F","T","A","U","A")
 letter=grade.count("A")
 print(letter)

#### A program that gives values in "A" to "D"

 grade=["A","B","C","F","T","U","D"]
 grade.sort()
 print(grade)
