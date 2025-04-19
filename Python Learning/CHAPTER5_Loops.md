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

## 🧠 06 – Loops

### 🔑 Learnings:
- Bsics of Loop 
- Benifits of Loop
- Working of While Loop
- Break and Countinue in Loop
- Basics of For Loop 
- Working of For Loop
- Learned That Where we use while and where we use For
- Range in Loops
- PASS statement
- Programs of While Loop
- Programs of For Loop


# Practice code:


### While Loop

count=1
while count <=5 : 
    print("Hello World")
    count+=1

print(count)

i = 1
while i<=10:
    print("Umair" , i )
    i+=1
print(i) 

i = 10
while i>=1:
    print(i )
    i-=1
print("Loop Ended") 

#### Program Print number from 1 to 100

i=1
while i<=100:
    print(i)
    i+=1
print("Loop End")

#### Program Print number from 100 to 1

i=100
while i>=1:
    print(i)
    i-=1
print("Loop End")

#### Program to get a multiple of number n

n=int(input("Enter Number to Print Table :"))
i=1
while i<=10:
    print( n ,"X", i,"=", n*i)
    i+=1
print("Your Table is END")


#### Program to print list numbers

num=[1,4,9,16,25,36,49,64,81,100]
idex=0

while idex <=len(num)-1:
    print(num[idex])
    idex+=1

print("Loop END")

#### Program to search number x from tuple

num1=int(input("ENTER NUM1 :"))
num2=int(input("ENTER NUM2 :"))
num3=int(input("ENTER NUM3 :"))
num4=int(input("ENTER NUM4 :"))
num5=int(input("ENTER NUM5 :"))
num6=int(input("ENTER NUM6 :"))
num7=int(input("ENTER NUM7 :"))
num8=int(input("ENTER NUM8 :"))

num=(num1,num2,num3,num4,num5,num6,num7,num8)
x=int(input("ENTER NUMBER To Search :"))
i=0
while i<len(num):
    if(num[i] == x):
        print("FOUND AT INDEX ", i)
    i+=1


#### Break

i=1
while i<=5:
    print(i)
    if(i==4):
        break
    i+=1

print("END")

### For loop 

tup=(1,2,3,4,5,6,7,8,9)

for val in tup:
    print(val)

#### Program to print numbers in list

list=[1,2,3,4,5,6,7,8,9]

for char in list:
    print(char)

print("END")

#### Program to search numbers in tuple

num1=int(input("ENTER NUM1 :"))
num2=int(input("ENTER NUM2 :"))
num3=int(input("ENTER NUM3 :"))
num4=int(input("ENTER NUM4 :"))
num5=int(input("ENTER NUM5 :"))
num6=int(input("ENTER NUM6 :"))
num7=int(input("ENTER NUM7 :"))
num8=int(input("ENTER NUM8 :"))
index=0

t=(num1,num2,num3,num4,num5,num6,num7,num8)
x=int(input("ENTER A NUMEBR TO SEARCH IN TUPLE :"))
for char in t:
    if(char == x):
        print("Found at index :" , index)
    index+=1

print("END")


### Range

for i in range(10):
    print(i)


#### Program print number from 1 to 100

for i in range(1,101):
    print(i)

#### Program print number from 100 to 1

for i in range(100,0, -1):
    print(i)

#### Program print multiplication number of n
n=int(input("ENTER NUMBER TO GET TABLE :"))
for i in range(1,11):
    print(n ,"X" ,i,"=",n*i )


#### Program print the sum of number n

n=int(input("ENTER NUMBER :"))
sum=0
i=1
while i<=n:
    sum+=i
    i +=1
print("TOTAL SUM IS THIS :" , sum)

#### Program to find factorial of number x

x=int(input("ENTER NUMBER :"))
fact=1
for i  in range(1,x+1):
    fact *=i
print("TOTAL FACTORIAL IS THIS :", fact)
