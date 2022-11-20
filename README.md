# Question 1

### **Question:**

> ***Write a program to add two numbers.***

---------------------------------------

<strong>Solution: </strong>

```python
a = 1
b = 2
c= a+b
print(c)
```
----------------------------------------

```python
a = int(input("Enter a number: "))
b = int(input("Enter a number: "))
c= a+b
print(c)
```
----------------------------------------

# Question 2

### **Question:**

> ***Write a program to find whether a given number (accept from the user) is even or odd, print out an appropriate message to the user.***

---------------------------------------

<strong>Solution: </strong>

```python
a = int(input("Enter a number: "))
if a % 2 == 0:
    print("This is an even number.")
else:
    print("This is an odd number.")
```
----------------------------------------

# Question 3

### **Question:**

> ***Write a program to check whether a number entered by the user is positive, negative or zero.***

---------------------------------------

<strong>Solution: </strong>

```python
a = int(input("Enter a number: "))
if a > 0:
   print("Positive number")
elif a == 0:
   print("Zero")
else:
   print("Negative number")
```
----------------------------------------

# Question 4

### **Question:**

> ***Write a program to display the calendar of a given date.***

---------------------------------------

<strong>Solution: </strong>

```python
import calendar
yy = int(input("Enter year: "))
mm = int(input("Enter month: "))
print(calendar.month(yy, mm))
```
----------------------------------------

# Question 5

### **Question:**

> ***Write a program to ask the user to enter the string and print that string as output of the program.***

---------------------------------------

<strong>Solution: </strong>

```python
x= input("Enter string: ")
print("You entered:", x)
```
----------------------------------------

# Question 6

### **Question:**

> ***Write a program to concatenate two strings.***

---------------------------------------

<strong>Solution: </strong>

```python
x = input("Enter first string to concatenate: ")
y = input("Enter second string to concatenate: ")
z = x + y
print("String after concatenation = ", z)
```
----------------------------------------

# Question 7

### **Question:**

> ***Write a program to check if an item exists in the list.***

---------------------------------------

<strong>Solution: </strong>

```python
x = ["ball", "book", "pencil"]
i = input("Type item to check: ")
if i in x:
 print("Item exists in the list.")
else:
  print("Item does not exist in the list.") 
```
----------------------------------------

# Question 8

### **Question:**

> ***Write a program to join two or more lists.***

---------------------------------------

<strong>Solution: </strong>

```python
x = ["This" , "is", "a", "blood", "sample"]
y = [20, 6, 55, 3, 9, 7, 18, 20]
z = x + y
print(z) 
```
----------------------------------------

# Question 9

### **Question:**

> ***Write a program to calculate cube of a number.***

---------------------------------------

<strong>Solution: </strong>

```python
import math 
x = int(input("Enter a number: "))
y=math.pow(x,3)
print(y) 
```
----------------------------------------

# Question 10

### **Question:**

> ***Write a program to calculate square root of a number.***

---------------------------------------

<strong>Solution: </strong>

```python
import math 
x = int(input("Enter a number: "))
y=math.sqrt(x)
print(y)  
```
----------------------------------------

# Question 11

### **Question:**

> ***Write a program that takes a list of numbers (for example, i = [6, 10, 75, 60, 55]) and makes a new list of only the first and last elements of the given list.***

---------------------------------------

<strong>Solution: </strong>

```python
i = [6, 10, 75, 60, 55]
print([i[0], i[4]]) 
```
----------------------------------------

# Question 12

### **Question:**

> ***Take a list, say for example this one: x = [1, 1, 2, 3, 2, 8, 18, 31, 14, 25, 78] and write a program that prints out all the elements of the list that are less than 4.***

---------------------------------------

<strong>Solution: </strong>

```python
x = [1, 1, 2, 3, 2, 8, 18, 31, 14, 25, 78]
for i in x:
    if i < 4:
        print(i)
```
----------------------------------------


# Question 13

### **Question:**

> ***Let's say I give you a list saved in a variable: x = [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]. Write one line of Python that takes this list 'x' and makes a new list that has only the even elements of this list in it.***

---------------------------------------

<strong>Solution: </strong>

```python
x = [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
y = [i for i in a if i % 2 == 0]
print(y)
```
----------------------------------------

# Question 14

### **Question:**

> ***Ask the user for a string and print out whether this string is a palindrome or not (A palindrome is a string that reads the same forwards and backwards).***

---------------------------------------

<strong>Solution: </strong>

```python
x=input("Please enter a word: ")
z = x.casefold()
y = reversed(z)
if list(z) == list(y):
   print("It is palindrome")
else:
   print("It is not palindrome")
```
----------------------------------------

# Question 15

### **Question:**

> ***Take two lists, say for example these two: x = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89] y = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13] and write a program that returns a list that contains only the elements that are common between the lists (without duplicates). Make sure your program works on two lists of different sizes.***

---------------------------------------

<strong>Solution: </strong>

```python
x = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]
y = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13]
print([i for i in set(x) if i in y])
```
----------------------------------------

# Question 16

### **Question:**

> ***Write a program to add a string to text file.***

---------------------------------------

<strong>Solution: </strong>

```python
file = open("testfile.txt","w") 
file.write("Albert Einstein") 
file.write("Elsa Einstein") 
file.write("David Einstein.") 
file.write("Why E=mc squared?.") 
file.close()
```
----------------------------------------

# Question 17

### **Question:**

> ***Write a program to read a file and display its contents on console.***

---------------------------------------

<strong>Solution: </strong>

```python
with open('testfile.txt') as f:
  	i = f.readline()
  	while i:
  		print(i)
  		line = f.readline()
```
----------------------------------------

# Question 18

### **Question:**

> ***Take two sets, say for example these two: x = {1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89} y = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13} and write a program that returns a set that contains only the elements that are common between the sets.***

---------------------------------------

<strong>Solution: </strong>

```python
x = {1, 1, 2, 2, 3, 5, 8, 13, 21, 34, 55, 89}
y = {1, 2, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13}
print(set(x) & set(y))
```
----------------------------------------

# Question 19

### **Question:**

> ***Write a program to split the characters of the given string into a list.***

---------------------------------------

<strong>Solution: </strong>

```python
x= "albert"
y = list(x)
print(y)
```
----------------------------------------

# Question 20

### **Question:**

> ***Create a program that asks the user for a number and then prints out a list of all the divisors of that number.***

---------------------------------------

<strong>Solution: </strong>

```python
x=int(input("Enter an integer: "))
print("The divisors of the number are: ")
for i in range(1,x+1):
    if(x%i==0):
        print(i)
```
----------------------------------------

# Question 21

### **Question:**

> ***Write a program to Find the largest of three numbers.***

---------------------------------------

<strong>Solution: </strong>

```python
x = int(input("Enter first number: "))
y = int(input("Enter second number: "))
z = int(input("Enter third number: "))
if (x > y) and (x > z):
   largest = x
elif (y > x) and (y > z):
   largest = y
else:
   largest = z
print("The largest number is", largest)
```
----------------------------------------

# Question 22

### **Question:**

> ***Write a program to find absolute value of a number.***

---------------------------------------

<strong>Solution: </strong>

```python
x = int(input("Enter a number: "))
if x >= 0:
		print(x)
else:
		print(-x)
```
----------------------------------------

# Question 23

### **Question:**

> ***Write a program to find the length of a string.***

---------------------------------------

<strong>Solution: </strong>

```python

print("Enter 'y' for exit.")
i = input("Enter a string: ")
if i == 'y':
    exit()
else:
    print("Length of the string is: ", len(i))
    
```
----------------------------------------

# Question 24

### **Question:**

> ***Write a program to print natural numbers from 1 to x.***

---------------------------------------

<strong>Solution: </strong>

```python
x = int(input("Please Enter any Number: "))
for i in range(1, x+1):
    print(i)
```
----------------------------------------


# Question 25

### **Question:**

> ***Write a program to calculate the sum and average of natural numbers from 1 to x.***

---------------------------------------

<strong>Solution: </strong>

```python
x = int(input("Please Enter any Number: "))
sum = 0
for i in range(1,x+1):
  sum = sum + i
print(sum)
average = sum / x
print(average)
```
----------------------------------------


# Question 26

### **Question:**

> ***Write a program to print a statement any number of times.***

---------------------------------------

<strong>Solution: </strong>

```python
x = int(input("Please Enter any Number: "))
for i in range(x):
    print("Albert Einstein")
```
----------------------------------------

# Question 27

### **Question:**

> ***Write a program to multiply two numbers using Function.***

---------------------------------------

<strong>Solution: </strong>

```python
def myfunc():
    x = int(input("Enter a number: "))
    y=int(input("Enter a number: "))
    z= x*y
    return z
i = myfunc()
print(i)
```
----------------------------------------

# Question 28

### **Question:**

> ***Write a program to add an item to the end of the list.***

---------------------------------------

<strong>Solution: </strong>

```python
x = ["pen", "book", "ball"]
x.append("bat")
print(x)
```
----------------------------------------

# Question 29

### **Question:**

> ***Write a program to remove an item from the list.***

---------------------------------------

<strong>Solution: </strong>

```python
x = ["pen", "book", "ball"]
x.remove("ball")
print(x)
```
----------------------------------------

# Question 30

### **Question:**

> ***Write a program to print the number of elements in an array.***

---------------------------------------

<strong>Solution: </strong>

```python
x = ["pen", "book", "ball"]
y = len(x)
print(y)
```
----------------------------------------

# Question 31

### **Question:**

> ***Write a program to calculate the variance and standard deviation of the elements of the list.***

---------------------------------------

<strong>Solution: </strong>

```python
import numpy as np
x= [2,6,8,12,18,24,28,32]
variance= np.var(x)
std = np.std(x)
print(variance)
print(std)
```
----------------------------------------


# Question 32

### **Question:**

> ***Write a program to get the difference between the two lists.***

---------------------------------------

<strong>Solution: </strong>

```python
x = [4, 5, 6, 7]
y = [4, 5]
print(list(set(x) - set(y)))
```
----------------------------------------

# Question 33

### **Question:**

> ***Write a program to select an item randomly from a list.***

---------------------------------------

<strong>Solution: </strong>

```python
import random
x = ['Paper', 'Pencil', 'Book', 'Bag', 'Pen']
print(random.choice(x))
```
----------------------------------------

# Question 34

### **Question:**

> ***Write a program that prints all the numbers from 0 to 6 except 2 and 6.***

---------------------------------------

<strong>Solution: </strong>

```python
for x in range(6):
    if (x == 2 or x==6):
        continue
    print(x)
```
----------------------------------------

# Question 35

### **Question:**

> ***Write a program that takes input from the user and displays that input back in upper and lower cases.***

---------------------------------------

<strong>Solution: </strong>

```python
x = input("What is your name? ")
print(x.upper())
print(x.lower())
```
----------------------------------------

# Question 36

### **Question:**

> ***Write a program to check whether a string starts with specified characters.***

---------------------------------------

<strong>Solution: </strong>

```python
x = "science.com"
print(x.startswith("phy"))
```
----------------------------------------

# Question 37

### **Question:**

> ***Write a program to create the multiplication table (from 1 to 10) of a number.***

---------------------------------------

<strong>Solution: </strong>

```python
x = int(input("Enter a number: "))
for i in range(1,11):
   print(x,'x',i,'=',x*i)
```
----------------------------------------

# Question 38

### **Question:**

> ***Write a program to check a triangle is equilateral, isosceles or scalene.***

---------------------------------------

<strong>Solution: </strong>

```python
print("Enter lengths of the triangle sides: ")
x = int(input("x: "))
y = int(input("y: "))
z = int(input("z: "))
if x == y == z:
	print("Equilateral triangle")
elif x==y or y==z or z==x:
	print("isosceles triangle")
else:
	print("Scalene triangle")
```
----------------------------------------


# Question 39

### **Question:**

> ***Write a program to sum of two given integers. However, if the sum is between 15 to 20 it will return 20.***

---------------------------------------

<strong>Solution: </strong>

```python
x = int(input("Enter a number: "))
y = int(input("Enter a number: "))
z= x+y
if z in range(15, 20):
        print (20)
else:
        print(z) 
```
----------------------------------------

# Question 40

### **Question:**

> ***Write a program to convert degree to radian.***

---------------------------------------

<strong>Solution: </strong>

```python
pi=22/7
degree = int(input("Input degrees: "))
radian = degree*(pi/180)
print(radian)
```
----------------------------------------


# Question 41

### **Question:**

> ***Write a program to generate a random number.***

---------------------------------------

<strong>Solution: </strong>

```python
import random
print(random.randint(0,9))
```
----------------------------------------


# Question 42

### **Question:**

> ***Write a program to find the semi-perimeter of triangle.***

---------------------------------------

<strong>Solution: </strong>

```python
x = int(input('Enter first side: '))
y = int(input('Enter second side: '))
z = int(input('Enter third side: '))
s = (x + y + z) / 2
print(s)
```
----------------------------------------


# Question 43

### **Question:**

> ***Given a list of numbers, iterate it and print only those numbers which are divisible of 2.***

---------------------------------------

<strong>Solution: </strong>

```python
x = [10, 20, 33, 46, 55]
for i in x:
    if (i % 2 == 0):
      print(i)
```
----------------------------------------

# Question 44

### **Question:**

> ***Write a program to multiply all numbers in the list.***

---------------------------------------

<strong>Solution: </strong>

```python
import numpy  
x = [1, 2, 3]  
y = numpy.prod(x) 
print(y) 
```
----------------------------------------

# Question 45

### **Question:**

> ***Write a program to print ASCII Value of a character.***

---------------------------------------

<strong>Solution: </strong>

```python
x = 'j'
print("The ASCII value of '" + x + "' is", ord(x))  
```
----------------------------------------

# Question 46

### **Question:**

> ***Write a program to print "#" without a newline or space.***

---------------------------------------

<strong>Solution: </strong>

```python
for x in range(0, 5):
    print('#', end="")
print("\n")
 
```
----------------------------------------


# Question 47

### **Question:**

> ***Write a program that will convert a string to a float or an integer.***

---------------------------------------

<strong>Solution: </strong>

```python
x = "546.11235"
print(float(x))
print(int(float(x)))
 
```
----------------------------------------


# Question 48

### **Question:**

> ***Write a program to add and search data in the dictionary.***

---------------------------------------

<strong>Solution: </strong>

```python
# Define a dictionary
customers = {'1':'Mehzabin Afroze','2':'Md. Ali',
'3':'Mosarof Ahmed','4':'Mila Hasan', '5':'Yaqub Ali'}

# Append a new data
customers['6'] = 'Mehboba Ferdous'

print("The customer names are:")
# Print the values of the dictionary
for customer in customers:
    print(customers[customer])

# Take customer ID as input to search
name = input("Enter customer ID:")

# Search the ID in the dictionary
for customer in customers:
    if customer == name:
        print(customers[customer])
        break
 
```
----------------------------------------

# Question 49

### **Question:**

> ***Write a program to obtain the details of the math module.***

---------------------------------------

<strong>Solution: </strong>

```python

import math             
print(dir(math))
 
```
----------------------------------------

# Question 50

### **Question:**

> ***Write a program to demonstrate throw and catch exception.***

---------------------------------------

<strong>Solution: </strong>

```python
# Try block
try:
    # Take a number
    x = int(input("Enter a number: "))
    if x % 2 == 0:
        print("Number is even")
    else:
        print("Number is odd")

# Exception block    
except (ValueError):
  # Print error message
  print("Enter a numeric value")
 
```
----------------------------------------

# Question 51

### **Question:**

> ***Write a program to illustrate password authentication.***

---------------------------------------

<strong>Solution: </strong>

```python
# import getpass module
import getpass

# Take password from the user
passwd = getpass.getpass('Password:')

# Check the password
if passwd == "albert":
    print("You are authenticated")
else:
    print("You are not authenticated")
 
```
----------------------------------------

# Question 52

### **Question:**

> ***Write a program to calculate the average of numbers in a given list.***

---------------------------------------

<strong>Solution: </strong>

```python
x=int(input("Enter the number of elements to be inserted: "))
y=[]
for i in range(0,x):
    n=int(input("Enter element: "))
    y.append(n)
avg=sum(y)/x
print("Average of elements in the list: ",round(avg,2))
 
```
----------------------------------------

# Question 53

### **Question:**

> ***Write a program that sorts three integers without the need of loops or conditional statements.***

---------------------------------------

<strong>Solution: </strong>

```python

a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))
c = int(input("Enter the third number: "))

x = min(a, b, c)
z = max(a, b, c)
y = (a + b + c) - x - z
print("Numbers in sorted order: ", x, y, z)

```
----------------------------------------

# Question 54

### **Question:**

> ***Write a program to determine the sum of digits of a number.***

---------------------------------------

<strong>Solution: </strong>

```python

num = int(input("Enter a four digit number: "))
x  = num //1000
y = (num - x*1000)//100
z = (num - x*1000 - y*100)//10
c = num - x*1000 - y*100 - z*10
print("The number's digits add up to: ", x+y+z+c)
 
```
----------------------------------------

# Question 55

### **Question:**

> ***Write a program to take in the marks of 5 subjects and display the grade.***

---------------------------------------

<strong>Solution: </strong>

```python
sub1=int(input("Enter marks of the first subject: "))
sub2=int(input("Enter marks of the second subject: "))
sub3=int(input("Enter marks of the third subject: "))
sub4=int(input("Enter marks of the fourth subject: "))
sub5=int(input("Enter marks of the fifth subject: "))
avg=(sub1+sub2+sub3+sub4+sub4)/5
if(avg>=90):
    print("Grade: A")
elif(avg>=80 and avg<90):
    print("Grade: B")
elif(avg>=70 and avg<80):
    print("Grade: C")
elif(avg>=60 and avg<70):
    print("Grade: D")
else:
    print("Grade: F")
 
```
----------------------------------------


# Question 56

### **Question:**

> ***Write a program to print all numbers in a range divisible by a given number.***

---------------------------------------

<strong>Solution: </strong>

```python
 
x=int(input("Enter lower range limit: "))
y=int(input("Enter upper range limit: "))
n=int(input("Enter the number to be divided by: "))
for i in range(x,y+1):
    if(i%n==0):
        print(i)
 
```
----------------------------------------

# Question 57

### **Question:**

> ***Write a program to read two numbers and print their quotient and remainder.***

---------------------------------------

<strong>Solution: </strong>

```python
 
a=int(input("Enter the first number: "))
b=int(input("Enter the second number: "))
quotient=a//b
remainder=a%b
print("Quotient is:", quotient)
print("Remainder is:", remainder)
 
```
----------------------------------------

# Question 58

### **Question:**

> ***Write a program to determine whether a given value is present in a collection of values.***

---------------------------------------

<strong>Solution: </strong>

```python
 
def myfunc(x, i):
   for value in x:
       if i == value:
           return True
   return False
print(myfunc([19, 15, 18, 13], 13))
print(myfunc([15, 18, 13], -11))
 
```
----------------------------------------


# Question 59

### **Question:**

> ***Write a program to print odd numbers within a given range.***

---------------------------------------

<strong>Solution: </strong>

```python
 
x=int(input("Enter the lower limit for the range: "))
y=int(input("Enter the upper limit for the range: "))
for i in range(x,y+1):
    if(i%2!=0):
        print(i)
 
```
----------------------------------------


# Question 60

### **Question:**

> ***Write a program to find the smallest divisor of an integer.***

---------------------------------------

<strong>Solution: </strong>

```python
 
n=int(input("Enter an integer:"))
a=[]
for i in range(2,n+1):
    if(n%i==0):
        a.append(i)
a.sort()
print("Smallest divisor is:",a[0])
 
```
----------------------------------------


# Question 61

### **Question:**

> ***Write a program to count the number of digits in a number.***

---------------------------------------

<strong>Solution: </strong>

```python
 
n=int(input("Enter a number:"))
i=0
while(n>0):
    i=i+1
    n=n//10
print("The number of digits in the number are:", i)
 
```
----------------------------------------


# Question 62

### **Question:**

> ***Write a program to read a number n and print and compute the series "1+2+…+n=".***

---------------------------------------

<strong>Solution: </strong>

```python
 
n=int(input("Enter a number: "))
x=[]
for i in range(1, n+1):
    print(i, sep=" ", end=" ")
    if(i<n):
        print("+", sep=" ", end=" ")
    x.append(i)
print("=",sum(x))
 
print()
 
```
----------------------------------------


# Question 63

### **Question:**

> ***Write a program to read a number n and print the natural numbers summation pattern.***

---------------------------------------

<strong>Solution: </strong>

```python

n=int(input("Enter a number: "))
for j in range(1, n+1):
    x=[]
    for i in range(1, j+1):
        print(i, sep=" ", end=" ")
        if(i<j):
            print("+",sep=" ",end=" ")
        x.append(i)
    print("=", sum(x))
 
print()
 
```
----------------------------------------


# Question 64

### **Question:**

> ***Write a program to read a number n and print an identity matrix of the desired size.***

---------------------------------------

<strong>Solution: </strong>

```python

n=int(input("Enter a number: "))
for i in range(0, n):
    for j in range(0, n):
        if(i==j):
            print("1", sep=" ", end=" ")
        else:
            print("0", sep=" ", end=" ")
    print()
 
```
----------------------------------------


# Question 65

### **Question:**

> ***Write a program to read a number n and print an inverted star pattern of the desired size.***

---------------------------------------

<strong>Solution: </strong>

```python

n=int(input("Enter number of rows: "))
for i in range (n,0,-1):
    print((n-i) * ' ' + i * '*')
 
```
----------------------------------------


# Question 66

### **Question:**

> ***Write a program to determine the hypotenuse of a right-angled triangle.***

---------------------------------------

<strong>Solution: </strong>

```python

from math import sqrt
print("Enter the lengths of shorter triangle sides: ")
x = float(input("x: "))
y = float(input("y: "))
z = sqrt(x**2 + y**2)
print("The length of the hypotenuse is: ", z)

 
```
----------------------------------------

# Question 67

### **Question:**

> ***Write a program to find the largest number in a list.***

---------------------------------------

<strong>Solution: </strong>

```python
x=[]
n=int(input("Enter number of elements: "))
for i in range(1, n+1):
    y=int(input("Enter element: "))
    x.append(y)
x.sort()
print("Largest element is: ",x[n-1])
 
```
----------------------------------------

# Question 68

### **Question:**

> ***Write a program to find the second largest number in a list.***

---------------------------------------

<strong>Solution: </strong>

```python
x=[]
n=int(input("Enter number of elements: "))
for i in range(1,n+1):
    y=int(input("Enter element: "))
    x.append(y)
x.sort()
print("Second largest element is: ",x[n-2])
 
```
----------------------------------------

# Question 69

### **Question:**

> ***Write a program to put the even and odd elements in a list into two different lists.***

---------------------------------------

<strong>Solution: </strong>

```python
a=[]
n=int(input("Enter number of elements:"))
for i in range(1,n+1):
    b=int(input("Enter element:"))
    a.append(b)
even=[]
odd=[]
for j in a:
    if(j%2==0):
        even.append(j)
    else:
        odd.append(j)
print("The even list", even)
print("The odd list", odd)
 
```
----------------------------------------

# Question 70

### **Question:**

> ***Write a program to concatenate all elements in a list into a string and return it.***

---------------------------------------

<strong>Solution: </strong>

```python
def myfunc(list):
    result= ''
    for i in list:
        result += str(i)
    return result

print(myfunc([2, 4, 13, 4]))
 
```
----------------------------------------


# Question 71

### **Question:**

> ***Write a program to add the three integers given. However, the sum will be zero if two values are equal.***

---------------------------------------

<strong>Solution: </strong>

```python
 
def myfunc(a, b, c):
    if a == b or b == c or a==c:
        sum = 0
    else:
        sum = a + b + c
    return sum
print(myfunc(12, 11, 12))
print(myfunc(13, 22, 22))
print(myfunc(22, 22, 22))
print(myfunc(12, 22, 13))

 
```
----------------------------------------

# Question 72

### **Question:**

> ***Write a program to sort a list according to the length of the elements.***

---------------------------------------

<strong>Solution: </strong>

```python
 
x=[]
n=int(input("Enter number of elements: "))
for i in range(1,n+1):
    y=input("Enter element: ")
    x.append(y)
x.sort(key=len)
print(x)
 
```
----------------------------------------

# Question 73

### **Question:**

> ***Write a program to create a list of tuples with the first element as the number and the second element as the square of the number.***

---------------------------------------

<strong>Solution: </strong>

```python
 
x=int(input("Enter the lower range:"))
y=int(input("Enter the upper range:"))
a=[(i,i**2) for i in range(x,y+1)]
print(a)
 
```
----------------------------------------


# Question 74

### **Question:**

> ***Write a program to create a list of all numbers in a range which are perfect squares and the sum of the digits of the number is less than 10.***

---------------------------------------

<strong>Solution: </strong>

```python
 
l=int(input("Enter lower range: "))
u=int(input("Enter upper range: "))
a=[]
a=[x for x in range(l,u+1) if (int(x**0.5))**2==x and sum(list(map(int,str(x))))<10]
print(a)
 
```
----------------------------------------


# Question 75

### **Question:**

> ***Write a program to convert a distance (in feet) to inches, yards, and miles.***

---------------------------------------

<strong>Solution: </strong>

```python
 

n = int(input("Enter the distance in feet: "))
x = n * 12
y = n / 3.0
z = n / 5280.0

print("The distance in inches is: %i inches." % x)
print("The distance in yards is: %.2f yards." % y)
print("The distance in miles is: %.2f miles." % z)
 
```
----------------------------------------


# Question 76

### **Question:**

> ***Write a program to generate random numbers from 1 to 20 and append them to the list.***

---------------------------------------

<strong>Solution: </strong>

```python
 
import random
a=[]
n=int(input("Enter number of elements:"))
for j in range(n):
    a.append(random.randint(1,20))
print('Randomised list is: ',a)
 
```
----------------------------------------


# Question 77

### **Question:**

> ***Write a program to sort a list of tuples in increasing order by the last element in each tuple.***

---------------------------------------

<strong>Solution: </strong>

```python
 
def last(n):
    return n[-1]  
 
def sort(tuples):
    return sorted(tuples, key=last)
 
a=input("Enter a list of tuples:")
print("Sorted:")
print(sort(a))
 
```
----------------------------------------


# Question 78

### **Question:**

> ***Write a program to determine whether the system is a big-endian or little-endian platform.***

---------------------------------------

<strong>Solution: </strong>

```python

import sys
print()
if sys.byteorder == "little":
    print("Little-endian platform.")
else:
    print("Big-endian platform.")
print()
 
```
----------------------------------------


# Question 79

### **Question:**

> ***Write a program to examine the available built-in modules.***

---------------------------------------

<strong>Solution: </strong>

```python

import sys
x = ', '.join(sorted(sys.builtin_module_names))
print("The available built-in modules are: ")
print()
print(x)
 
```
----------------------------------------


# Question 80

### **Question:**

> ***Write a program to determine an object's size in bytes.***

---------------------------------------

<strong>Solution: </strong>

```python

import sys
x = "three"
y = 154
z = [11, 12, 13, 'Ball', 'Bat']
print("Size of ",x,"=",str(sys.getsizeof(x))+ " bytes")
print("Size of ",y,"=",str(sys.getsizeof(y))+ " bytes")
print("Size of ",z,"=",str(sys.getsizeof(z))+ " bytes")
 
```
----------------------------------------


# Question 81

### **Question:**

> ***Write a program to concatenate 'n' strings.***

---------------------------------------

<strong>Solution: </strong>

```python

x = ['Stephen', 'William', 'Hawking']  
i = '-'.join(x)
print()
print(i)
print()
 
```
----------------------------------------


# Question 82

### **Question:**

> ***Write a program to display the current date and time.***

---------------------------------------

<strong>Solution: </strong>

```python

import datetime
 
print(datetime.datetime.now().strftime("%Y-%m-%d %H:%M:%S"))
 
```
----------------------------------------

# Question 83

### **Question:**

> ***Write a program to calculate the volume of a sphere with a radius of 8.***

---------------------------------------

<strong>Solution: </strong>

```python

pi=22/7
r = 8.0
V = 4.0/3.0*pi*r**3
print('The volume of the sphere is: ',V)

```
----------------------------------------

# Question 84

### **Question:**

> ***Write a program to check whether every number in a list exceeds a specific number.***

---------------------------------------

<strong>Solution: </strong>

```python

x = [12, 33, 44, 55]
print()
print(all(i > 11 for i in x))
print(all(i > 100 for i in x))
print()

```
----------------------------------------


# Question 85

### **Question:**

> ***Write a program that count the occurrences of a particular character within a given string.***

---------------------------------------

<strong>Solution: </strong>

```python

x = "Albert Einstein."  
print("Number of occurrence of 'e' in the given string: ")
print(x.count("e"))
 
```
----------------------------------------

# Question 86

### **Question:**

> ***Write a program to compute simple interest given all the required values.***

---------------------------------------

<strong>Solution: </strong>

```python
x=float(input("Enter the principal amount: "))
y=float(input("Enter the rate: "))
z=int(input("Enter the time (years): "))
simple_interest=(x*y*z)/100
print("The simple interest is: ", simple_interest)
 
```
----------------------------------------

# Question 87

### **Question:**

> ***Write a program to check whether a given year is a leap year or not.***

---------------------------------------

<strong>Solution: </strong>

```python

year=int(input("Enter the year to be checked: "))
if(year%4==0 and year%100!=0 or year%400==0):
    print("The", year, "is a leap year!")
else:
    print("The", year, "isn't a leap year!")

 
```
----------------------------------------

# Question 88

### **Question:**

> ***Write a program that determines if a file path points to a file or a directory.***

---------------------------------------

<strong>Solution: </strong>

```python
import os  
path="1.txt"  
if os.path.isdir(path):  
    print("It is a directory")  
elif os.path.isfile(path):  
    print("It is a regular file")  
else:  
    print("It is a unique file (socket, FIFO, device file)" )
print()
 
```
----------------------------------------


# Question 89

### **Question:**

> ***Write a program to generate all the divisors of an integer.***

---------------------------------------

<strong>Solution: </strong>

```python
 
x=int(input("Enter an integer: "))
print("The divisors of", x, "are: ")
for i in range(1, x+1):
    if(x%i==0):
        print(i)
 
```
----------------------------------------

# Question 90

### **Question:**

> ***Write a program to print the table of a given number.***

---------------------------------------

<strong>Solution: </strong>

```python
 
n=int(input("Enter the number to print the tables for: "))
for i in range(1,11):
    print(n,"x",i,"=",n*i)
 
```
----------------------------------------

# Question 91

### **Question:**

> ***Write a program to check if a number is an Armstrong number.***

---------------------------------------

<strong>Solution: </strong>

```python
 
n=int(input("Enter any number: "))
a=list(map(int,str(n)))
b=list(map(lambda x:x**3,a))
if(sum(b)==n):
    print("The number", n, "is an armstrong number. ")
else:
    print("The number", n, "isn't an arsmtrong number. ")
 
```
----------------------------------------


# Question 92

### **Question:**

> ***Write a program to find Python site-packages.***

---------------------------------------

<strong>Solution: </strong>

```python
 
import site 
print(site.getsitepackages())
 
```
----------------------------------------


# Question 93

### **Question:**

> ***Write a program to check if a number is a perfect number.***

---------------------------------------

<strong>Solution: </strong>

```python
 
x = int(input("Enter any number: "))
sum = 0
for i in range(1, x):
    if(x % i == 0):
        sum = sum + i
if (sum == x):
    print("The number", x, "is a perfect number!")
else:
    print("The number", x, "is not a perfect number!")
 
```
----------------------------------------


# Question 94

### **Question:**

> ***Write a program to find the LCM of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```python
 
x=int(input("Enter the first number: "))
y=int(input("Enter the second number: "))
if(x>y):
    min=x
else:
    min=y
while(1):
    if(min%x==0 and min%y==0):
        print("LCM is:",min)
        break
    min=min+1
 
```
----------------------------------------


# Question 95

### **Question:**

> ***Write a program to find the GCD of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```python
 
import math
x=int(input("Enter the first number: "))
y=int(input("Enter the second number: "))
print("The GCD of the two numbers is", math.gcd(x,y))
 
```
----------------------------------------


# Question 96

### **Question:**

> ***Write a program to determine a file's size.***

---------------------------------------

<strong>Solution: </strong>

```python

import os
x = os.path.getsize("1.csv")
print("The size of 1.csv is:", x, "Bytes")
print()
 
```
----------------------------------------


# Question 97

### **Question:**

> ***Write a program to check if two numbers are amicable numbers.***

---------------------------------------

<strong>Solution: </strong>

```python

x=int(input('Enter number 1: '))
y=int(input('Enter number 2: '))
sum1=0
sum2=0
for i in range(1,x):
    if x%i==0:
        sum1+=i
for j in range(1,y):
    if y%j==0:
        sum2+=j
if(sum1==y and sum2==x):
    print('Amicable!')
else:
    print('Not Amicable!')
 
```
----------------------------------------


# Question 98

### **Question:**

> ***Write a program to find the area of a triangle given all three sides.***

---------------------------------------

<strong>Solution: </strong>

```python

import math
a=int(input("Enter first side: "))
b=int(input("Enter second side: "))
c=int(input("Enter third side: "))
s=(a+b+c)/2
area=math.sqrt(s*(s-a)*(s-b)*(s-c))
print("Area of the triangle is: ",round(area,2))
 
```
----------------------------------------


# Question 99

### **Question:**

> ***Write a program to find the gravitational force acting between two objects.***

---------------------------------------

<strong>Solution: </strong>

```python

m1=float(input("Enter the first mass: "))
m2=float(input("Enter the second mass: "))
r=float(input("Enter the distance between the centres of the masses: "))
G=6.673*(10**-11)
f=(G*m1*m2)/(r**2)
print("Hence, the gravitational force is: ",round(f,2),"N")

 
```
----------------------------------------


# Question 100

### **Question:**

> ***Write a program to determine if a string is numeric.***

---------------------------------------

<strong>Solution: </strong>

```python

x = 'x549'
try:
    i = float(x)
    print('Numeric')
except (ValueError, TypeError):
    print('Not numeric')
print()

 
```
----------------------------------------

# Question 101

### **Question:**

> ***Write a program to find out which host the routine is running on.***

---------------------------------------

<strong>Solution: </strong>

```python

import socket
x = socket.gethostname()
print("Host name: ", x)

 
```
----------------------------------------

# Question 102

### **Question:**

> ***Write a program to find the sum of first n positive integers.***

---------------------------------------

<strong>Solution: </strong>

```python

n=int(input("Enter a number: "))
sum = 0
while(n > 0):
    sum=sum+n
    n=n-1
print("The sum of first n positive integers is: ", sum)
 
```

----------------------------------------

```python

n = int(input("Enter a number: "))
sum = (n * (n + 1)) / 2
print("The sum of first", n ,"positive integers is:", sum)
 
```

----------------------------------------
# Question 103

### **Question:**

> ***Write a program to find the sum of series: 1 + 1/2 + 1/3 + ….. + 1/n.***

---------------------------------------

<strong>Solution: </strong>

```python
n=int(input("Enter the number of terms: "))
sum=0
for i in range(1,n+1):
    sum=sum+(1/i)
print("The sum of series is: ", round(sum,2))
 
```
----------------------------------------

# Question 104

### **Question:**

> ***Write a program to get numbers divisible by 12 from a list using an anonymous function.***

---------------------------------------

<strong>Solution: </strong>

```python

x = [55, 144, 72, 155, 120, 135, 540]
result = list(filter(lambda i: (i % 15 == 0), x))
print("Numbers divisible by 12 are: ", result)
 
```
----------------------------------------

# Question 105

### **Question:**

> ***Write a program to format a given string with a string length limitation.***

---------------------------------------

<strong>Solution: </strong>

```python

x = "987653421066"
print('%.5s' % x)
print('%.7s' % x)
print('%.9s' % x)

 
```
----------------------------------------

# Question 106

### **Question:**

> ***Write a program that accepts a number as input and returns an error if it is not a number.***

---------------------------------------

<strong>Solution: </strong>

```python
while True:
    try:
        a = int(input("Enter a number: "))
        print("This is a number")
        break
    except ValueError:
        print("This isn't a number")
        print()
 
 
```
----------------------------------------


# Question 107

### **Question:**

> ***Write a program to filter the negative numbers from a list.***

---------------------------------------

<strong>Solution: </strong>

```python
 
x = [22, -10, 11, -28, 52, -75]
y = list(filter(lambda i: i <0, x))
print("Negative numbers in the above list: ", y)
 
```
----------------------------------------

# Question 108

### **Question:**

> ***Write a program to find whether a number is a power of two.***

---------------------------------------

<strong>Solution: </strong>

```python
 
def myfunc(n):
    """Return True if n is a power of two."""
    if n <= 0:
        return False
    else:
        return n & (n - 1) == 0
 
 
n = int(input('Enter a number: '))
 
if myfunc(n):
    print('{} is a power of two.'.format(n))
else:
    print('{} is not a power of two.'.format(n))
 
```
----------------------------------------

# Question 109

### **Question:**

> ***Write a program to solve (a - b) * (a - b).***

---------------------------------------

<strong>Solution: </strong>

```python
 
a, b = 2, 4
result = a * a - 2 * a * b + b * b
print("({} - {}) ^ 2 = {}".format(a, b, result))
 
```
----------------------------------------


# Question 110

### **Question:**

> ***Write a program to generate a new string with the prefix "Al" from a given string. Return the given text in its original form if it already contains the "Al" prefix.***

---------------------------------------

<strong>Solution: </strong>

```python
 
def myfunc(x):
  if len(x) >= 2 and x[:2] == "Al":
    return x
  return "Al" + x
print(myfunc("Albert"))
print(myfunc("bert"))
 
```
----------------------------------------


# Question 111

### **Question:**

> ***Write a program that count all occurrences of the number 5 in a list.***

---------------------------------------

<strong>Solution: </strong>

```python
 
def myfunc(y):
  i = 0  
  for x in y:
    if x == 5:
      i = i + 1

  return i

print(myfunc([11, 5, 16, 18, 15]))
print(myfunc([17, 14, 5, 12, 9, 5]))

```
----------------------------------------


# Question 112

### **Question:**

> ***Write a program to determine if a file is present.***

---------------------------------------

<strong>Solution: </strong>

```python

import os.path
print(os.path.isfile('1.txt'))
print(os.path.isfile('1.pdf'))
 
```
----------------------------------------


# Question 113

### **Question:**

> ***Write a program to replace all occurrences of 'a' with '$' in a string.***

---------------------------------------

<strong>Solution: </strong>

```python

x=input("Enter string: ")
x=x.replace('a','$')
x=x.replace('A','$')
print("Modified string: ")
print(x)
 
```
----------------------------------------

# Question 114

### **Question:**

> ***Write a program to calculate the product of a list of numbers (without using for loop).***

---------------------------------------

<strong>Solution: </strong>

```python
from functools import reduce
num = [2, 4, 10,11]
result = reduce( (lambda x, y: x * y), num)
print("Product of the above numbers is: ", result)
 
```
----------------------------------------

# Question 115

### **Question:**

> ***Write a program to detect if two strings are anagrams.***

---------------------------------------

<strong>Solution: </strong>

```python
x=input("Enter first string: ")
y=input("Enter second string: ")
if(sorted(x)==sorted(y)):
      print("The 2 strings are anagrams.")
else:
      print("The 2 strings aren't anagrams.")

 
```
----------------------------------------

# Question 116

### **Question:**

> ***Write a program to form a string where the first character and the last character have been exchanged.***

---------------------------------------

<strong>Solution: </strong>

```python

def change(x):
      return x[-1:] + x[1:-1] + x[:1]
x=input("Enter a string: ")
print("Modified string: ")
print(change(x))
 
```
----------------------------------------


# Question 117

### **Question:**

> ***Write a program to count the number of vowels in a string.***

---------------------------------------

<strong>Solution: </strong>

```python
 
string=input("Enter string:")
vowels=0
for i in string:
      if(i=='a' or i=='e' or i=='i' or i=='o' or i=='u' or i=='A' or i=='E' or i=='I' or i=='O' or i=='U'):
            vowels=vowels+1
print("Number of vowels are:")
print(vowels)
 
```
----------------------------------------

# Question 118

### **Question:**

> ***Write a program to take a string and replace every blank space with a hyphen.***

---------------------------------------

<strong>Solution: </strong>

```python
 
string=input("Enter a string: ")
string=string.replace(' ','-')
print("Modified string:")
print(string)
 
```
----------------------------------------

# Question 119

### **Question:**

> ***Write a program to calculate the length of a string without using library functions.***

---------------------------------------

<strong>Solution: </strong>

```python
 
s=input("Enter string: ")
x=0
for i in s:
      x=x+1
print("Length of the string is: ")
print(x)
 
```
----------------------------------------


# Question 120

### **Question:**

> ***Write a program to determine whether lowercase letters are present in a string.***

---------------------------------------

<strong>Solution: </strong>

```python

x = 'Albert Einstein'
print(any(i.islower() for i in x))
 
```
----------------------------------------


# Question 121

### **Question:**

> ***Write a program to calculate the number of words and characters present in a string.***

---------------------------------------

<strong>Solution: </strong>

```python
 
x=input("Enter a string: ")
char=0
word=1
for i in x:
      char=char+1
      if(i==' '):
            word=word+1
print("Number of words in the string: ")
print(word)
print("Number of characters in the string: ")
print(char)
 
```
----------------------------------------


# Question 122

### **Question:**

> ***Write a program that rounds a floating-point integer to a specified number of decimal places.***

---------------------------------------

<strong>Solution: </strong>

```python
 
x = 549.968
print('%f' % x)
print('%.2f' % x)
print()
 
```
----------------------------------------


# Question 123

### **Question:**

> ***Write a program to count number of lowercase characters in a string.***

---------------------------------------

<strong>Solution: </strong>

```python
 
x=input("Enter string: ")
count=0
for i in x:
      if(i.islower()):
            count=count+1
print("The number of lowercase characters is: ")
print(count)
 
```
----------------------------------------


# Question 124

### **Question:**

> ***Write a program to count the number of lowercase letters and uppercase letters in a string.***

---------------------------------------

<strong>Solution: </strong>

```python

x=input("Enter a string: ")
count1=0
count2=0
for i in x:
      if(i.islower()):
            count1=count1+1
      elif(i.isupper()):
            count2=count2+1
print("The number of lowercase characters is: ")
print(count1)
print("The number of uppercase characters is: ")
print(count2)
 
```
----------------------------------------


# Question 125

### **Question:**

> ***Write a program to calculate the number of digits and letters in a string.***

---------------------------------------

<strong>Solution: </strong>

```python

x=input("Enter a string: ")
count1=0
count2=0
for i in x:
      if(i.isdigit()):
            count1=count1+1
      count2=count2+1
print("The number of digits is: ")
print(count1)
print("The number of characters is: ")
print(count2)
 
```
----------------------------------------


# Question 126

### **Question:**

> ***Write a program to form a new string made of the first 2 characters and last 2 characters from a given string.***

---------------------------------------

<strong>Solution: </strong>

```python

x=input("Enter a string: ")
count=0
for i in x:
      count=count+1
new=x[0:2]+x[count-2:count]
print("Newly formed string is: ")
print(new)
 
```
----------------------------------------


# Question 127

### **Question:**

> ***Write a program to create a bytearray from a list.***

---------------------------------------

<strong>Solution: </strong>

```python

x = [10, 20, 56, 35, 17, 99]
# Create bytearray from list of integers.
y = bytearray(x)
for i in y: print(i)
print()

```
----------------------------------------


# Question 128

### **Question:**

> ***Write a program to determine whether an integer fits in 64 bits.***

---------------------------------------

<strong>Solution: </strong>

```python

x = 60
if x.bit_length() <= 63:
    print((-2 ** 63).bit_length())
    print((2 ** 63).bit_length())

 
```
----------------------------------------

# Question 129

### **Question:**

> ***Write a program that returns true if the two given integer values are equal, or if their sum or difference is 10.***

---------------------------------------

<strong>Solution: </strong>

```python

def myfunc(a, b):
   if a == b or abs(a-b) == 10 or (a+b) == 10:
       return True
   else:
       return False
print(myfunc(17, 2))
print(myfunc(30, 20))
print(myfunc(5, 5))
print(myfunc(17, 13))
print(myfunc(53, 73))
 
```
----------------------------------------

# Question 130

### **Question:**

> ***Write a program to add two objects if they are both of the integer type.***

---------------------------------------

<strong>Solution: </strong>

```python

def myfunc(x, y):
   if not (isinstance(x, int) and isinstance(y, int)):
       return "Inputs have to be integers only!"
   return x + y
print(myfunc(50, 70))
print(myfunc(20, 50.74))
print(myfunc('6', 8))
print(myfunc('8', '8'))

```
----------------------------------------

# Question 131

### **Question:**

> ***Write a program to add leading zeros to a string.***

---------------------------------------

<strong>Solution: </strong>

```python
x='122.22'
x = x.ljust(8, '0')
print(x)
x = x.ljust(10, '0')
print(x)
 
```
----------------------------------------

# Question 132

### **Question:**

> ***Write a program that displays strings with double quotes.***

---------------------------------------

<strong>Solution: </strong>

```python

import json
print(json.dumps({'Albert': 1, 'Alan': 2, 'Alex': 3}))
 
```
----------------------------------------

# Question 133

### **Question:**

> ***Write a program to check if a given key exists in a dictionary or not.***

---------------------------------------

<strong>Solution: </strong>

```python

d={'A':1,'B':2,'C':3}
key=input("Enter key to check:")
if key in d.keys():
      print("Key is present and value of the key is:")
      print(d[key])
else:
      print("Key isn't present!")

```
----------------------------------------

# Question 134

### **Question:**

> ***Write a program to find the sum all the items in a dictionary.***

---------------------------------------

<strong>Solution: </strong>

```python

d={'A':100,'B':540,'C':239}
print("Total sum of values in the dictionary is: ")
print(sum(d.values()))
 
 
```
----------------------------------------


# Question 135

### **Question:**

> ***Write a program to multiply all the items in a dictionary.***

---------------------------------------

<strong>Solution: </strong>

```python
 
d={'A':10,'B':10,'C':239}
x=1
for i in d:    
    x=x*d[i]
print(x)
 
```
----------------------------------------

# Question 136

### **Question:**

> ***Write a program to remove the given key from a dictionary.***

---------------------------------------

<strong>Solution: </strong>

```python
 
d = {'a':1,'b':2,'c':3,'d':4}
print("Initial dictionary")
print(d)
key=input("Enter the key to delete(a-d):")
if key in d: 
    del d[key]
else:
    print("Key not found!")
    exit(0)
print("Updated dictionary")
print(d)
 
```
----------------------------------------

# Question 137

### **Question:**

> ***Write a program to list the home directory without using an absolute path.***

---------------------------------------

<strong>Solution: </strong>

```python
 
import os.path
print(os.path.expanduser('~'))
 
```
----------------------------------------


# Question 138

### **Question:**

> ***Write a program to input two integers in a single line.***

---------------------------------------

<strong>Solution: </strong>

```python

print("Enter the value of a and b: ")
a, b = map(int, input().split())
print("The value of a and b are: ", a, b)
 
```
----------------------------------------


# Question 139

### **Question:**

> ***Write a program to convert true to 1 and false to 0.***

---------------------------------------

<strong>Solution: </strong>

```python
 
a = 'true'
a = int(a == 'true')
print(a)
a = 'xyz'
a = int(a == 'true')
print(a)

 
```
----------------------------------------


# Question 140

### **Question:**

> ***Write a program to determine whether a variable is an integer or a string.***

---------------------------------------

<strong>Solution: </strong>

```python
 
print(isinstance(16,int) or isinstance(16,str))
print(isinstance("16",int) or isinstance("16",str))
 
```
----------------------------------------


# Question 141

### **Question:**

> ***Write a program to count the number of vowels present in a string entered by the user using sets.***

---------------------------------------

<strong>Solution: </strong>

```python
 
s=input("Enter a string: ")
count = 0
vowels = set("aeiou")
for letter in s:
    if letter in vowels:
        count += 1
print("The number of vowels present in a string is: ")
print(count)
 
```
----------------------------------------


# Question 142

### **Question:**

> ***Write a program to check common letters in the two input strings.***

---------------------------------------

<strong>Solution: </strong>

```python

x=input("Enter the first string: ")
y=input("Enter the second string: ")
z=list(set(x)&set(y))
print("The common letters are: ")
for i in z:
    print(i)
    
```
----------------------------------------


# Question 143

### **Question:**

> ***Write a program to display which letters are in the first string but not in the second string.***

---------------------------------------

<strong>Solution: </strong>

```python

x=input("Enter the first string: ")
y=input("Enter the second string: ")
z=list(set(x)-set(y))
print("The letters in the first string but not in the second string are: ")
for i in z:
    print(i)
    
```
----------------------------------------


# Question 144

### **Question:**

> ***Write a program to determine whether a variable is a list, tuple, or set.***

---------------------------------------

<strong>Solution: </strong>

```python

i = ['list', True, 8.9, 6]
if type(i) is list:
    print('i is a list')
elif type(i) is set:
    print('i is a set')
elif type(i) is tuple:
    print('i is a tuple')    
else:
    print('Neither a set, list, or tuple.')
 
```
----------------------------------------


# Question 145

### **Question:**

> ***Write a program to determine whether a given number is even or odd recursively.***

---------------------------------------

<strong>Solution: </strong>

```python

def myfunc(n):
    if (n < 2):
        return (n % 2 == 0)
    return (myfunc(n - 2))
n=int(input("Enter a number: "))
if(myfunc(n)==True):
      print("Number is even!")
else:
      print("Number is odd!")

 
```
----------------------------------------


# Question 146

### **Question:**

> ***Write a program that examines a list of numbers to see if they are all distinct from one another.***

---------------------------------------

<strong>Solution: </strong>

```python

def myfunc(x):
  if len(x) == len(set(x)):
    return True
  else:
    return False;
print(myfunc([11,15,17,19]))
print(myfunc([12,14,15,15,17,19]))

 
```
----------------------------------------

# Question 147

### **Question:**

> ***Write a program to add two positive numbers without using the '+' operator.***

---------------------------------------

<strong>Solution: </strong>

```python

def myfunc(x, y):
    while y != 0:
        z = x & y
        x = x ^ y
        y = z << 1
    return x
print(myfunc(12, 50))

 
```
----------------------------------------

# Question 148

### **Question:**

> ***Write a program to find the factorial of a number using recursion.***

---------------------------------------

<strong>Solution: </strong>

```python

def myfunc(n):
    if(n <= 1):
        return 1
    else:
        return(n*myfunc(n-1))
n = int(input("Enter a number: "))
print("Factorial of", n, "is:", myfunc(n))

 
```
----------------------------------------
# Question 149

### **Question:**

> ***Write a program to determine whether a right triangle is formed by three given side lengths. If the specified sides make a right triangle, print "Yes," otherwise print "No."***

---------------------------------------

<strong>Solution: </strong>

```python
print("Enter three side lengths of a triangle: ")
a,b,c = sorted(list(map(int,input().split())))
if a**2+b**2==c**2:
    print('Yes')
else:
    print('No')
 
```
----------------------------------------

# Question 150

### **Question:**

> ***Write a program to find the number of equal numbers among three given integers.***

---------------------------------------

<strong>Solution: </strong>

```python
def myfunc(a, b, c):
  result= set([a, b, c])
  if len(result)==3:
    return 0
  else:
    return (4 - len(result))

print(myfunc(11, 11, 11))
print(myfunc(11, 12, 12))
 
```
----------------------------------------

# Question 151

### **Question:**

> ***Write a program to find the LCM of two numbers using recursion.***

---------------------------------------

<strong>Solution: </strong>

```python
def lcm(a,b):
    lcm.multiple=lcm.multiple+b
    if((lcm.multiple % a == 0) and (lcm.multiple % b == 0)):
        return lcm.multiple;
    else:
        lcm(a, b)
    return lcm.multiple
lcm.multiple=0
a=int(input("Enter first number:"))
b=int(input("Enter second number:"))
if(a>b):
    LCM=lcm(b,a)
else:
    LCM=lcm(a,b)
print(LCM)

 
```
----------------------------------------

# Question 152

### **Question:**

> ***Write a program to find the GCD of two numbers using recursion.***

---------------------------------------

<strong>Solution: </strong>

```python
def gcd(a,b):
    if(b==0):
        return a
    else:
        return gcd(b,a%b)
a=int(input("Enter first number:"))
b=int(input("Enter second number:"))
GCD=gcd(a,b)
print("GCD is: ")
print(GCD)
 
 
```
----------------------------------------


# Question 153

### **Question:**

> ***Write a program to read the contents of a file.***

---------------------------------------

<strong>Solution: </strong>

```python
 
a=str(input("Enter the name of the file with .txt extension:"))
file2=open(a,'r')
line=file2.readline()
while(line!=""):
    print(line)
    line=file2.readline()
file2.close()
 
```
----------------------------------------

# Question 154

### **Question:**

> ***Write a program to count the number of words in a text file.***

---------------------------------------

<strong>Solution: </strong>

```python
 
fname = input("Enter file name: ")
 
num_words = 0
 
with open(fname, 'r') as f:
    for line in f:
        words = line.split()
        num_words += len(words)
print("Number of words:")
print(num_words)
 
```
----------------------------------------

# Question 155

### **Question:**

> ***Write a program to count the number of lines in a text file.***

---------------------------------------

<strong>Solution: </strong>

```python
 
fname = input("Enter file name: ")
num_lines = 0
with open(fname, 'r') as f:
    for line in f:
        num_lines += 1
print("Number of lines:")
print(num_lines)
 
```
----------------------------------------


# Question 156

### **Question:**

> ***Write a program to read a string from the user and appends it into a file.***

---------------------------------------

<strong>Solution: </strong>

```python

fname = input("Enter file name: ")
file3=open(fname,"a")
c=input("Enter string to append: \n");
file3.write("\n")
file3.write(c)
file3.close()
print("Contents of appended file:");
file4=open(fname,'r')
line1=file4.readline()
while(line1!=""):
    print(line1)
    line1=file4.readline()    
file4.close()
 
```
----------------------------------------


# Question 157

### **Question:**

> ***Write a program to count the occurrences of a word in a text file.***

---------------------------------------

<strong>Solution: </strong>

```python
 
fname = input("Enter file name: ")
word=input("Enter word to be searched:")
k = 0
 
with open(fname, 'r') as f:
    for line in f:
        words = line.split()
        for i in words:
            if(i==word):
                k=k+1
print("Occurrences of the word:")
print(k)
 
```
----------------------------------------


# Question 158

### **Question:**

> ***Write a program to copy the contents of one file into another.***

---------------------------------------

<strong>Solution: </strong>

```python
 
with open("test.txt") as f:
    with open("out.txt", "w") as f1:
        for line in f:
            f1.write(line)
 
```
----------------------------------------


# Question 159

### **Question:**

> ***Write a program to count the occurrences of a letter in a text file.***

---------------------------------------

<strong>Solution: </strong>

```python
 
fname = input("Enter file name: ")
l=input("Enter letter to be searched:")
k = 0
 
with open(fname, 'r') as f:
    for line in f:
        words = line.split()
        for i in words:
            for letter in i:
                if(letter==l):
                    k=k+1
print("Occurrences of the letter:")
print(k)
 
```
----------------------------------------


# Question 160

### **Question:**

> ***Write a program to read a text file and print all numbers present in the text file.***

---------------------------------------

<strong>Solution: </strong>

```python

fname = input("Enter file name: ")
 
with open(fname, 'r') as f:
    for line in f:
        words = line.split()
        for i in words:
            for letter in i:
                if(letter.isdigit()):
                    print(letter)
 
```
----------------------------------------


# Question 161

### **Question:**

> ***Write a program to append the contents of one file to another file.***

---------------------------------------

<strong>Solution: </strong>

```python

name1 = input("Enter file to be read from: ")
name2 = input("Enter file to be appended to: ")
fin = open(name1, "r")
data2 = fin.read()
fin.close()
fout = open(name2, "a")
fout.write(data2)
fout.close()
 
```
----------------------------------------


# Question 162

### **Question:**

> ***Write a program to count the number of blank spaces in a text file.***

---------------------------------------

<strong>Solution: </strong>

```python

fname = input("Enter file name: ")
k = 0
 
with open(fname, 'r') as f:
    for line in f:
        words = line.split()
        for i in words:
            for letter in i:
                if(letter.isspace):
                    k=k+1
print("Occurrences of blank spaces:")
print(k)
 
```
----------------------------------------


# Question 163

### **Question:**

> ***Write a program to read a file and capitalize the first letter of every word in the file.***

---------------------------------------

<strong>Solution: </strong>

```python

fname = input("Enter file name: ")
 
with open(fname, 'r') as f:
    for line in f:
        l=line.title()
        print(l)

 
```
----------------------------------------


# Question 164

### **Question:**

> ***Write a program to read the contents of a file in reverse order.***

---------------------------------------

<strong>Solution: </strong>

```python

filename=input("Enter file name: ")
for line in reversed(list(open(filename))):
    print(line.rstrip())

 
```
----------------------------------------

# Question 165

### **Question:**

> ***Write a program to find the area of a rectangle using classes.***

---------------------------------------

<strong>Solution: </strong>

```python

class rectangle():
    def __init__(self,breadth,length):
        self.breadth=breadth
        self.length=length
    def area(self):
        return self.breadth*self.length
a=int(input("Enter length of rectangle: "))
b=int(input("Enter breadth of rectangle: "))
obj=rectangle(a,b)
print("Area of rectangle:",obj.area())
 
print()

 
```
----------------------------------------

# Question 166

### **Question:**

> ***Write a program to append, delete and display elements of a list using classes.***

---------------------------------------

<strong>Solution: </strong>

```python

class check():
    def __init__(self):
        self.n=[]
    def add(self,a):
        return self.n.append(a)
    def remove(self,b):
        self.n.remove(b)
    def dis(self):
        return (self.n)
 
obj=check()
 
choice=1
while choice!=0:
    print("0. Exit")
    print("1. Add")
    print("2. Delete")
    print("3. Display")
    choice=int(input("Enter choice: "))
    if choice==1:
        n=int(input("Enter number to append: "))
        obj.add(n)
        print("List: ",obj.dis())
 
    elif choice==2:
        n=int(input("Enter number to remove: "))
        obj.remove(n)
        print("List: ",obj.dis())
 
    elif choice==3:
        print("List: ",obj.dis())
    elif choice==0:
        print("Exiting!")
    else:
        print("Invalid choice!!")
 
print()
 
```
----------------------------------------
# Question 167

### **Question:**

> ***Write a program that calculate the difference between a given number and 10, returning double the absolute difference if the value is higher than 10.***

---------------------------------------

<strong>Solution: </strong>

```python

def myfunc(x):
    if x <= 10:
        return 10 - x
    else:
        return (x - 10) * 2 

print(myfunc(8))
print(myfunc(16))
 
```
----------------------------------------

# Question 168

### **Question:**

> ***Write a program that add three given numbers, returning three times their sum if the values are equivalent.***

---------------------------------------

<strong>Solution: </strong>

```python

def myfunc(a, b, c):

     sum = a + b + c
  
     if a == b == c:
      sum = sum * 3
     return sum

print(myfunc(11, 12, 13))
print(myfunc(13, 13, 13))

```
----------------------------------------

# Question 169

### **Question:**

> ***Write a program to check whether an OS is running a Python shell in 32 or 64 bit mode.***

---------------------------------------

<strong>Solution: </strong>

```python
import platform
print(platform.architecture()[0])

```
----------------------------------------

# Question 170

### **Question:**

> ***Write a program to implement birthday dictionary.***

---------------------------------------

<strong>Solution: </strong>

```python
if __name__ == '__main__':

    birthdays = {
        'Albert Einstein': '03/14/1879',
        'Benjamin Franklin': '01/17/1706',
        'Ada Lovelace': '12/10/1815',
        'Donald Trump': '06/14/1946',
        'Rowan Atkinson': '01/6/1955'}

    print('Welcome to the birthday dictionary. We know the birthdays of:')
    for name in birthdays:
        print(name)

    print('Who\'s birthday do you want to look up?')
    name = input()
    if name in birthdays:
        print('{}\'s birthday is {}.'.format(name, birthdays[name]))
    else:
        print('Sadly, we don\'t have {}\'s birthday.'.format(name))
 
```
----------------------------------------


# Question 171

### **Question:**

> ***Write a program to find the name and location of the file that is currently running.***

---------------------------------------

<strong>Solution: </strong>

```python
 
import os
print("Current File Name : ",os.path.realpath(__file__))
 
```
----------------------------------------

# Question 172

### **Question:**

> ***Write a program to implement password generator.***

---------------------------------------

<strong>Solution: </strong>

```python
 
import random
x = "abcdefghijklmnopqrstuvwxyz01234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ!@#$%^&*()?"
passlen = 8
print("".join(random.sample(x, passlen)))
 
```
----------------------------------------

# Question 173
### **Question:**

> ***Write a program to display calendar of the given month and year.***

---------------------------------------

<strong>Solution: </strong>

```python
 
# importing calendar module
import calendar

yy = 2014  # year
mm = 11    # month

# To take month and year input from the user
# yy = int(input("Enter year: "))
# mm = int(input("Enter month: "))

# display the calendar
print(calendar.month(yy, mm))
 
```
----------------------------------------



# Question 174

### **Question:**

> ***Write a program to add two matrices.***

---------------------------------------

<strong>Solution: </strong>

```python

X = [[12,7,3],
    [4 ,5,6],
    [7 ,8,9]]

Y = [[5,8,1],
    [6,7,3],
    [4,5,9]]

result = [[0,0,0],
         [0,0,0],
         [0,0,0]]

# iterate through rows
for i in range(len(X)):
   # iterate through columns
   for j in range(len(X[0])):
       result[i][j] = X[i][j] + Y[i][j]

for r in result:
   print(r)
 
```
----------------------------------------


# Question 175

### **Question:**

> ***Write a program to transpose a matrix.***

---------------------------------------

<strong>Solution: </strong>

```python
 
X = [[12,7],
    [4 ,5],
    [3 ,8]]

result = [[0,0,0],
         [0,0,0]]

# iterate through rows
for i in range(len(X)):
   # iterate through columns
   for j in range(len(X[0])):
       result[j][i] = X[i][j]

for r in result:
   print(r)
 
```
----------------------------------------


# Question 176

### **Question:**

>***Write a program to count the number of CPUs being used.***

---------------------------------------

<strong>Solution: </strong>

```python
 
import multiprocessing
print(multiprocessing.cpu_count())
 
```
----------------------------------------


# Question 177

### **Question:**

> ***Write a program to reverse a string if its length is a multiple of 6.***

---------------------------------------

<strong>Solution: </strong>

```python
 
def myfunc(x):
    if len(x) % 6 == 0:
       return ''.join(reversed(x))
    return x

print(myfunc('alan'))
print(myfunc('albert'))
 
```
----------------------------------------


# Question 178

### **Question:**

> ***Put "xyz" at the end of the specified string (length should be at least 3). If the provided string already ends with "xyz," add "123" to it. If the specified string's length is less than three, leave it unaltered.***

---------------------------------------

<strong>Solution: </strong>

```python

def myfunc(x):
  i = len(x)

  if i > 2:
    if x[-3:] == 'xyz':
      x += '123'
    else:
      x += 'xyz'

  return x

print(myfunc('xy'))
print(myfunc('xyz'))
print(myfunc('morning'))

 
```
----------------------------------------


# Question 179

### **Question:**

> ***Write a program to shuffle the elements of a given list.***

---------------------------------------

<strong>Solution: </strong>

```python

import random 
x = [11, 12, 13, 14, 15]
random.shuffle(x)
print(x)
 
```
----------------------------------------


# Question 180

### **Question:**

> ***Three positive numbers are present in a list. Write a program to determine whether the sum of the digits in each number is equal or not. If true, return true; otherwise, return false.***

---------------------------------------

<strong>Solution: </strong>

```python

def myfunc(x):
    return x[0] % 9 == x[1] % 9 == x[2] % 9 
x = [14, 5, 23]
print(myfunc(x))

```
----------------------------------------


# Question 181

### **Question:**

> ***Write a program to get IP address of your computer.***

---------------------------------------

<strong>Solution: </strong>

```python
import socket    
x = socket.gethostname()    
y = socket.gethostbyname(x)    
print("Your Computer Name is: " + x)    
print("Your Computer IP Address is: " + y) 
```
----------------------------------------

# Question 182

### **Question:**

> ***Write a program to determine whether a series of integers has an increasing trend or not.***

---------------------------------------

<strong>Solution: </strong>

```python

def myfunc(x):
    if (sorted(x) == x):
        return True
    else:
        return False

print(myfunc([11,12,13,14]))
print(myfunc([11,12,15,13,14]))

```
----------------------------------------

# Question 183

### **Question:**

> ***Write a program to illustrate Dice Roll Simulator.***

---------------------------------------

<strong>Solution: </strong>

```python
import random
min = 1
max = 6

roll_again = "yes"

while roll_again == "yes" or roll_again == "y":
    print ("Rolling the dices...")
    print ("The values are....")
    print (random.randint(min, max))
    print (random.randint(min, max))

    roll_again = input("Roll the dices again?")
```
----------------------------------------


# Question 184

### **Question:**

> ***Write a program to convert the temperature in degree centigrade to Fahrenheit.***

---------------------------------------

<strong>Solution: </strong>

```python
c = input(" Enter temperature in Centigrade: ")
f = (9*(int(c))/5)+32
print(" Temperature in Fahrenheit is: ", f)
```
----------------------------------------

# Question 185

### **Question:**

> ***Write a program to check whether the given integer is a multiple of 5.***

---------------------------------------

<strong>Solution: </strong>

```python
x = int(input("Enter an integer: "))
if(x%5==0):
    print(x, "is a multiple of 5")
else:
    print(x, "is not a multiple of 5")
```
----------------------------------------

# Question 186

### **Question:**

> ***Write a program to check whether the given integer is a multiple of both 3 and 5.***

---------------------------------------

<strong>Solution: </strong>

```python
x = int(input("Enter an integer: "))
if((x%3==0)and(x%5==0)):
    print(x, "is a multiple of both 3 and 5")
else:
    print(x, "is not a multiple of both 3 and 5")
```
----------------------------------------


# Question 187

### **Question:**

> ***Write a program to display all the multiples of 5 within the range 10 to 70.***

---------------------------------------

<strong>Solution: </strong>

```python
for i in range(10,70):
    if (i%5==0):
        print(i)
```
----------------------------------------


# Question 188

### **Question:**

> ***Write a program to display all integers within the range 50-100 whose sum of digits is an even number.***

---------------------------------------

<strong>Solution: </strong>

```python
for i in range(50,100):
    num = i
    sum = 0
    while(num!=0):
        digit = num%10
        sum = sum + digit
        num = num//10
    if(sum%2==0):
        print(i)
```
----------------------------------------


# Question 189

### **Question:**

> ***Write a program to print the numbers from a given number n till 0 using recursion.***

---------------------------------------

<strong>Solution: </strong>

```python

def myfunc(n):
    if (n==0):
        return
    print(n)
    n=n-1
    myfunc(n)
myfunc(9)

```
----------------------------------------

# Question 190

### **Question:**

> ***Write a program to find the odd numbers in an array.***

---------------------------------------

<strong>Solution: </strong>

```python
num = [8,3,1,6,2,4,5,9]
count = 0
for i in range(len(num)):
    if(num[i]%2!=0):
        count = count+1
print("The number of odd numbers in the array are: ", count)
```
----------------------------------------

# Question 191

### **Question:**

> ***Write a program to reverse a given upper case string in lower case.***

---------------------------------------

<strong>Solution: </strong>

```python

def myfunc(x):
    return x[::-1].lower()
x = "JAVASCRIPT"
print(myfunc(x))

```
----------------------------------------

# Question 192

### **Question:**

> ***Write a program to find the maximum of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```python
def maximum(a, b):
     
    if a >= b:
        return a
    else:
        return b
     
a = 3
b = 5
print(maximum(a, b))
```
----------------------------------------

<strong>Solution: </strong>

```python
a = 3
b = 5
 
print(max(a, b))
```
----------------------------------------

<strong>Solution: </strong>

```python
a = 3
b = 5
 
print(a if a >= b else b)
```
----------------------------------------

# Question 193

### **Question:**

> ***Write a program to find the minimum of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```python
def minimum(a, b):
      
    if a <= b:
        return a
    else:
        return b
      
a = 3
b = 9
print(minimum(a, b))
```
----------------------------------------


# Question 194

### **Question:**

> ***Write a program to calculate Profit or Loss.***

---------------------------------------

<strong>Solution: </strong>

```python
cp=float(input("Enter the Cost Price : "));
sp=float(input("Enter the Selling Price : "));
if cp==sp:
    print("No Profit or No Loss")
else:
    if sp>cp:
        print("Profit of ",sp-cp)
    else:
        print("Loss of ",cp-sp)
```
----------------------------------------

# Question 195

### **Question:**

> ***Write a program to find Student Grade.***

---------------------------------------

<strong>Solution: </strong>

```python
physics = float(input(" Please enter Physics Marks: "))
math = float(input(" Please enter Math score: "))
chemistry = float(input(" Please enter Chemistry Marks: "))

total = physics + math + chemistry
percentage = (total / 300) * 100

print("Total Marks = %.2f"  %total)
print("Percentage = %.2f"  %percentage)

if(percentage >= 90):
    print("A Grade")
elif(percentage >= 80):
    print("B Grade")
elif(percentage >= 70):
    print("C Grade")
elif(percentage >= 60):
    print("D Grade")
elif(percentage >= 40):
    print("E Grade")
else:
    print("Fail")
```
----------------------------------------

# Question 196

### **Question:**

> ***Write a program to print Even numbers from 1 to N.***

---------------------------------------

<strong>Solution: </strong>

```python
x = int(input(" Enter the Value of N : "))

for num in range(1, x+1):
    if(num % 2 == 0):
        print("{0}".format(num))
```
----------------------------------------

# Question 197

### **Question:**

> ***Write a program to print Odd numbers from 1 to N.***

---------------------------------------

<strong>Solution: </strong>

```python
x = int(input(" Enter the Value of N : "))

for num in range(1, x+1):
    if(num % 2 != 0):
        print("{0}".format(num))
```
----------------------------------------

# Question 198

### **Question:**

> ***Write a program to compute sum of Even numbers from 1 to N.***

---------------------------------------

<strong>Solution: </strong>

```python
x = int(input(" Enter the Value of N : "))
total = 0

for num in range(1, x+1):
    if(num % 2 == 0):
        print("{0}".format(num))
        total = total + num

print("The Sum of Even Numbers from 1 to {0} is: {1}".format(num, total))
```
----------------------------------------


# Question 199

### **Question:**

> ***Write a program to compute sum of Odd numbers from 1 to N.***

---------------------------------------

<strong>Solution: </strong>

```python
x = int(input(" Enter the Value of N : "))
total = 0

for num in range(1, x+1):
    if(num % 2 != 0):
        print("{0}".format(num))
        total = total + num

print("The Sum of Odd Numbers from 1 to {0} is: {1}".format(num, total))
```
----------------------------------------


# Question 200

### **Question:**

> ***Write a program to check whether a character is Alphabet or not.***

---------------------------------------

<strong>Solution: </strong>

```python
ch = input("Enter a Character : ")

if((ch >= 'a' and ch <= 'z') or (ch >= 'A' and ch <= 'Z')):
    print(ch, "is an Alphabet.")
else:
    print(ch, "is Not an Alphabet.")
```
----------------------------------------

# Question 201

### **Question:**

> ***Write a program to check whether a character is Alphabet or Digit or Special Character.***

---------------------------------------

<strong>Solution: </strong>

```python
ch = input("Enter a Character : ")

if((ch >= 'a' and ch <= 'z') or (ch >= 'A' and ch <= 'Z')): 
    print(ch, "is an Alphabet.") 
elif(ch >= '0' and ch <= '9'):
    print(ch, "is a Digit.")
else:
    print(ch, "is a Special Character.")
```
----------------------------------------

# Question 202

### **Question:**

> ***Write a program to check whether a character is Lowercase or not.***

---------------------------------------

<strong>Solution: </strong>

```python
ch = input("Enter a Character : ")

if(ch.islower()):
    print(ch, "is a Lowercase character")
else:
    print(ch, "is Not a Lowercase character")
```
----------------------------------------


# Question 203

### **Question:**

> ***Write a program to check whether a character is Uppercase or not.***

---------------------------------------

<strong>Solution: </strong>

```python
ch = input("Enter a Character : ")

if(ch.isupper()):
    print(ch, "is a Uppercase character")
else:
    print(ch, "is Not a Uppercase character")
```
----------------------------------------

# Question 204

### **Question:**

> ***Write a program to check whether a character is Vowel or Consonant.***

---------------------------------------

<strong>Solution: </strong>

```python
ch = input("Enter a Character : ")

if(ch == 'a' or ch == 'e' or ch == 'i' or ch == 'o' or ch == 'u' or ch == 'A'
       or ch == 'E' or ch == 'I' or ch == 'O' or ch == 'U'):
    print(ch, "is a Vowel")
else:
    print(ch, "is a Consonant")
```
----------------------------------------

# Question 205

### **Question:**

> ***Write a program to convert string to Uppercase.***

---------------------------------------

<strong>Solution: </strong>

```python
str = input("Enter a String : ")

string = str.upper()
 
print("\nString in Lowercase  =  ", str)
print("String in Uppercase =  ", string)
```
----------------------------------------

# Question 206

### **Question:**

> ***Write a program to convert string to Lowercase.***

---------------------------------------

<strong>Solution: </strong>

```python
str = input("Enter a String : ")

string = str.lower()

print("\nString in Uppercase  =  ", str)
print("String in Lowercase =  ", string)
```
----------------------------------------
 

# Question 207

### **Question:**

> ***Write a program to convert Decimal to Binary, octal, and Hexadecimal.***

---------------------------------------

<strong>Solution: </strong>

```python

decimal = int(input("Enter a Decimal Number: "))

binary = bin(decimal)
octal = oct(decimal)
hexadecimal = hex(decimal)

print(decimal, " Decimal Value = ", binary, "Binary Value")
print(decimal, " Decimal Value = ", octal, "Octal Value")
print(decimal, " Decimal Value = ", hexadecimal, "Hexadecimal Value")
```
----------------------------------------

# Question 208

### **Question:**

> ***Write a program to check a Triangle is Valid or Not.***

---------------------------------------

<strong>Solution: </strong>

```python
a = int(input('Please Enter the First Angle of a Triangle: '))
b = int(input('Please Enter the Second Angle of a Triangle: '))
c = int(input('Please Enter the Third Angle of a Triangle: '))


total = a + b + c

if total == 180:
    print("\nThis is a Valid Triangle")
else:
    print("\nThis is an Invalid Triangle")
```
----------------------------------------

# Question 209

### **Question:**

> ***Write a program that inputs an age and print age after 20 years .***

---------------------------------------

<strong>Solution: </strong>

```python
age = int(input("What is your age? "))
print("In twenty years, you will be", age + 20, "years old!")
```
----------------------------------------

# Question 210

### **Question:**

> ***Write a program to print the number of seconds in year.***

---------------------------------------

<strong>Solution: </strong>

```python
days=365
hours=24
minutes=60
seconds=60
print("Number of seconds in a year : ",days*hours*minutes*seconds)
```
----------------------------------------

# Question 211

### **Question:**

> ***Write a program that inputs a string and then prints it equal to number of times its length.***

---------------------------------------

<strong>Solution: </strong>

```python
str = input("Enter string: ")
b = len(str)
a = str * b
print(a)
```
----------------------------------------




