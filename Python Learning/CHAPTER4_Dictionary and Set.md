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

## 🧠 04 – Lists and Tuples

### 🔑 Learnings:
- Dictionary in python
- Nested Dictionary in python
- Dictionary Methods
- Sets in Python
- Sets Method
- Practice Programs 


## Practice code:


# Dictionary

 info ={
    "name" : "Umair Saeed",
     "cgpa" : 96.4,
    "key" : "value",
     "is_Adult" : True,
     "age" : 89    
 }

 print(info["name"])

# NESTED DICTIONARY 

 info={
    "name" : "ABC",
     "age" : 56,
     "marks" : {
         "phy" : 89,
         "chem" : 56,
         "comp" : 100,
         "bio" : 56
     },
     "class" : "online",
     "time" : 10.55,
 }

 print(info)
# Dictionary Methods

 print(info.keys())
 print(info.values())

# sets 

 coll={1,2,3,4,5,6,7,8,9,2,3,3,}
 coll.add(896)
 coll.add(897)
 coll.add(898)
 coll.remove(898)
 print(coll)

# Practice programs 

 words={
     "table" : ["a piece of furniture", "list of fact and figures"],
     "cat" : "a small animal"
 }

 print(words)


 set={"python" , "java", "C++","python","javascript","java","python","java","C++","C"}
 print(len(set))

 mark={}

 phy=int(input("Enter Marks of Physics :"))
 mark.update({"phy" : phy}) 

 chem=int(input("Enter Marks of Chemistry :"))
mark.update({"chem" : chem}) 

 bio=int(input("Enter Marks of Physics :"))
 mark.update({"bio" : bio}) 

 print(mark)