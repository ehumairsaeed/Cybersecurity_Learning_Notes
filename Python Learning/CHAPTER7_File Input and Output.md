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

## 🧠 01 – File Input and Output

### 🔑 Learnings:
- File I/O
- Reading data from files
- Writing data in files
- Deleting the files
- Importing module
- Practice Programs

# Practice Code



### File Input and Output

f = open("demo.txt" , "a+")

data=f.read()
f.write("\nHey You ARE NOT A GOOD PERSON. \nI also Want to become a Hacker.")
print(data)
f.close()

#### File by with

with open("demo.txt" , "w") as file:
    file.write("Hey I am a Ethical Hacker")
    
#### Deleting File

import os

os.remove("sample.txt")


#### Program to  write data in file

with open("Practice.txt" , "rw") as file:
    file.write("HI everyone \n we are learning File I/O\n Using Java.\n I like programming in java")

#### Program to replace java with python

with open("Practice.txt" , "r") as file:
    data=file.read()

new=data.replace("Java" , "Python")
print(new)

with open("Practice.txt" , "w") as file:
    file.write(new)

#### Program to search word learning

with open("Practice.txt" , "r") as file:
    data=file.read()

fin=data.find("learning")
print(fin)


#### Program to check the line of word learning in fil

def check_line():
    data=True
    word="Using"
    line_no=1
    with open("Practice.txt" , "r") as fi:
        while data:
            data=fi.readline()
            if (word in data):
                print(line_no)
                return
            line_no+=1
    return -1

check_line()
    

#### Program to count total even numbers in file
count=0
with open("practice.txt" , "r") as f:
    data=f.read()
    
    nums=data.split(",")
    print(nums)

    for val in nums:
        if (int(val)%2 == 0):
            count+=1
        
print(count)
    
