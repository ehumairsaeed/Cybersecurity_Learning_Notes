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

## 🧠 01 – Functions and Recursion

### 🔑 Learnings:
- Funtions in Python
- Paremtters
- Arguments
- Funtion Call
- Types of funtion
- Default Parameters
- Basics of Recursion
- Practice Programs


# Practice Code


## Funtions in Python

def calc_sum(a,b):
    sum=a+b
    print(sum)
    return sum

#### Using Funtion 

calc_sum(5,9)

def check(c,d):
    cch=c==d
    return cch
c=int(input("NUMBER :"))
d=int(input("NUMBER :"))

b= check(c,d)
print(b)

#### Program to get a avarage of 3 numbers 

def avgf(a,b,c):
    av=(a+b+c)/3
    return av

a=int(input("ENTER NUMBER1 :"))
b=int(input("ENTER NUMBER2 :"))
c=int(input("ENTER NUMBER3 :"))

avg = int(avgf(a,b,c))
print(avg)

#### Program to print the length of list

l=[2,3,5,4,5,6,8,9,6,2,41,5,66,3,5,1,2,3,5,565,56,56,56,565,121,454,21,545,5]
b=[1,2,45,4,5,6,3,2,1,4,56,2,14,4,55,14,5,221,5]

def leng(list):
    return len(list)

print(leng(l))
print(leng(b))

#### Program to print element of list in single line 

b=[1,2,4,4,5,6,3,2]

def elem(list):
    # index=0
    for char in  list:
        print(char, end=" ")

elem(b)

#### Program to calculate the factorial of number n

a=int(input("ENTER NUMBER1 :"))

def fact(a):
    facte=1
    for num in range(1, a+1):
        facte*=num
    return facte

print(fact(a))    
    

#### Program to convert USD to PKR

usd=int(input("ENTER AMOUNT IN USD :"))
pkr=int(input("ENTER TODAY USD RATE IN PKR :"))

def curr(a,b):
    mul=a*b
    return mul

print(usd ,"USD =" , curr(usd,pkr),"PKR")


#### Program to check the number is even or odd
num=int(input("ENTER NUMBER :"))

def odev(a):
    if (a%2 == 0):
        print("THE NUMEBR IS EVEN")
    elif (a%2 != 0):
        print("THE NUMBER IS ODD")

odev(num)

### Recursion

n=6

def fact(a):
    if(a==0 or a==1):
        return 1
    else:
        return a*fact(a-1)

print(fact(n))


#### Program to calculate the sum of first to n of natural numbers 

n=int(input("ENTER A NUMBER :"))

def fact(a):
    if(a==0 or a==1):
        return 1
    else:
        return a+fact(a-1)

print(fact(n))


#### Program write a recursive  function to print all list elements

l = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]

def lli(a, index=0):
    if index == len(a):
        return
    print(a[index])
    lli(a, index + 1)

a = lli(l)
print(a)
