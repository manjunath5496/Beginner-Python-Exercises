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

> ***Write a program to list files in a directory.***

---------------------------------------

<strong>Solution: </strong>

```python
# Import os module to read directory
import os

# Set the directory path
path = 'C:/Users/Manju/.spyder-py3/'

# Read the content of the file
files = os.listdir(path)

# Print the content of the directory
for file in files:
    print(file)
 
```
----------------------------------------


# Question 47

### **Question:**

> ***Write a program to read and write file.***

---------------------------------------

<strong>Solution: </strong>

```python
#Assign the filename
filename = "languages.txt"
# Open file for writing
fileHandler = open(filename, "w")

# Add some text
fileHandler.write("Bash\n")
fileHandler.write("Python\n")
fileHandler.write("PHP\n")

# Close the file
fileHandler.close()

# Open file for reading
fileHandler = open(filename, "r")

# Read a file line by line
for line in fileHandler:
  print(line)
 
# Close the file
fileHandler.close()
 
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

> ***Write a program to add and search data in the set.***

---------------------------------------

<strong>Solution: </strong>

```python
# Define the number set
numbers = {23, 90, 56, 78, 12, 34, 67}
 
# Add a new data
numbers.add(50)
# Print the set values
print(numbers)

message = "Number is not found"

# Take a number value for search
search_number = int(input("Enter a number:"))
# Search the number in the set
for val in numbers:
    if val == search_number:
        message = "Number is found"
        break

print(message)
 
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

> ***Write a program to exchange the values of two numbers without using a temporary variable.***

---------------------------------------

<strong>Solution: </strong>

```python
a=int(input("Enter value of first variable: "))
b=int(input("Enter value of second variable: "))
a=a+b
b=a-b
a=a-b
print("a is:",a," b is:",b)
 
```
----------------------------------------

# Question 54

### **Question:**

> ***Write a program to reverse a given number.***

---------------------------------------

<strong>Solution: </strong>

```python
n=int(input("Enter number: "))
rev=0
while(n>0):
    dig=n%10
    rev=rev*10+dig
    n=n//10
print("Reverse of the number:",rev)
 
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
 
n=int(input("Enter number:"))
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
a=[]
for i in range(1,n+1):
    print(i,sep=" ",end=" ")
    if(i<n):
        print("+",sep=" ",end=" ")
    a.append(i)
print("=",sum(a))
 
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
for j in range(1,n+1):
    a=[]
    for i in range(1,j+1):
        print(i,sep=" ",end=" ")
        if(i<j):
            print("+",sep=" ",end=" ")
        a.append(i)
    print("=",sum(a))
 
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
for i in range(0,n):
    for j in range(0,n):
        if(i==j):
            print("1",sep=" ",end=" ")
        else:
            print("0",sep=" ",end=" ")
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

> ***Write a program to print prime numbers in a range using Sieve of Eratosthenes.***

---------------------------------------

<strong>Solution: </strong>

```python

n=int(input("Enter upper limit of range: "))
sieve=set(range(2,n+1))
while sieve:
    prime=min(sieve)
    print(prime,end="\t")
    sieve-=set(range(prime,n+1,prime))
 
print()

 
```
----------------------------------------

# Question 67

### **Question:**

> ***Write a program to find the largest number in a list.***

---------------------------------------

<strong>Solution: </strong>

```python
a=[]
n=int(input("Enter number of elements:"))
for i in range(1,n+1):
    b=int(input("Enter element:"))
    a.append(b)
a.sort()
print("Largest element is:",a[n-1])
 
```
----------------------------------------

# Question 68

### **Question:**

> ***Write a program to find the second largest number in a list.***

---------------------------------------

<strong>Solution: </strong>

```python
a=[]
n=int(input("Enter number of elements:"))
for i in range(1,n+1):
    b=int(input("Enter element:"))
    a.append(b)
a.sort()
print("Second largest element is:",a[n-2])
 
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
 
a=[]
n=int(input("Enter number of elements: "))
for i in range(1,n+1):
    b=input("Enter element: ")
    a.append(b)
a.sort(key=len)
print(a)
 
```
----------------------------------------

# Question 73

### **Question:**

> ***Write a program to create a list of tuples with the first element as the number and the second element as the square of the number.***

---------------------------------------

<strong>Solution: </strong>

```python
 
l_range=int(input("Enter the lower range:"))
u_range=int(input("Enter the upper range:"))
a=[(x,x**2) for x in range(l_range,u_range+1)]
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

> ***Write a program to find the cumulative sum of a list where the i<sup>th</sup> element is the sum of the first i+1 elements from the original list.***

---------------------------------------

<strong>Solution: </strong>

```python
 
a=[]
n= int(input("Enter the number of elements in list:"))
for x in range(0,n):
    element=int(input("Enter element" + str(x+1) + ":"))
    a.append(element)
b=[sum(a[0:x+1]) for x in range(0,len(a))]
print("The original list is: ",a)
print("The new list is: ",b)
 
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

> ***Write a program to swap the first and last value of a list.***

---------------------------------------

<strong>Solution: </strong>

```python

a=[]
n= int(input("Enter the number of elements in list:"))
for x in range(0,n):
    element=int(input("Enter element" + str(x+1) + ":"))
    a.append(element)
temp=a[0]
a[0]=a[n-1]
a[n-1]=temp
print("New list is:")
print(a)
 
```
----------------------------------------


# Question 79

### **Question:**

> ***Write a program to remove the duplicate items from a list.***

---------------------------------------

<strong>Solution: </strong>

```python

a=[]
n= int(input("Enter the number of elements in list:"))
for x in range(0,n):
    element=int(input("Enter element" + str(x+1) + ":"))
    a.append(element)
b = set()
unique = []
for x in a:
    if x not in b:
        unique.append(x)
        b.add(x)
print("Non-duplicate items:")
print(unique)
 
```
----------------------------------------


# Question 80

### **Question:**

> ***Write a program to read a list of words and return the length of the longest one.***

---------------------------------------

<strong>Solution: </strong>

```python

a=[]
n= int(input("Enter the number of elements in list:"))
for x in range(0,n):
    element=input("Enter element" + str(x+1) + ":")
    a.append(element)
max1=len(a[0])
temp=a[0]
for i in a:
    if(len(i)>max1):
       max1=len(i)
       temp=i
print("The word with the longest length is:")
print(temp)
 
```
----------------------------------------


# Question 81

### **Question:**

> ***Write a program to remove the i<sup>th</sup> occurrence of the given word in list where words can repeat.***

---------------------------------------

<strong>Solution: </strong>

```python

a=[]
n= int(input("Enter the number of elements in list:"))
for x in range(0,n):
    element=input("Enter element" + str(x+1) + ":")
    a.append(element)
print(a)
c=[]
count=0
b=input("Enter word to remove: ")
n=int(input("Enter the occurrence to remove: "))
for i in a:
    if(i==b):
        count=count+1
        if(count!=n):
            c.append(i)
    else:
        c.append(i)
if(count==0):
    print("Item not found ")
else: 
    print("The number of repetitions is: ",count)
    print("Updated list is: ",c)
    print("The distinct elements are: ",set(a))

 
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

> ***Write a program to find the element that occurs odd number of times in a list.***

---------------------------------------

<strong>Solution: </strong>

```python

def find_odd_occurring(alist):
    """Return the element that occurs odd number of times in alist.
 
    alist is a list in which all elements except one element occurs an even
    number of times.
    """
    ans = 0
 
    for element in alist:
        ans ^= element
 
    return ans
 
 
alist = input('Enter the list: ').split()
alist = [int(i) for i in alist]
ans = find_odd_occurring(alist)
print('The element that occurs odd number of times:', ans)

 
```
----------------------------------------


# Question 85

### **Question:**

> ***Write a program to check if a date is valid and print the incremented date if it is.***

---------------------------------------

<strong>Solution: </strong>

```python
date=input("Enter the date: ")
dd,mm,yy=date.split('/')
dd=int(dd)
mm=int(mm)
yy=int(yy)
if(mm==1 or mm==3 or mm==5 or mm==7 or mm==8 or mm==10 or mm==12):
    max1=31
elif(mm==4 or mm==6 or mm==9 or mm==11):
    max1=30
elif(yy%4==0 and yy%100!=0 or yy%400==0):
    max1=29
else:
    max1=28
if(mm<1 or mm>12):
    print("Date is invalid.")
elif(dd<1 or dd>max1):
    print("Date is invalid.")
elif(dd==max1 and mm!=12):
    dd=1
    mm=mm+1
    print("The incremented date is: ",dd,mm,yy)
elif(dd==31 and mm==12):
    dd=1
    mm=1
    yy=yy+1
    print("The incremented date is: ",dd,mm,yy)
else:
    dd=dd+1
    print("The incremented date is: ",dd,mm,yy)
 
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
year=int(input("Enter year to be checked:"))
if(year%4==0 and year%100!=0 or year%400==0):
    print("The year is a leap year!")
else:
    print("The year isn't a leap year!")

 
```
----------------------------------------

# Question 88

### **Question:**

> ***Write a program to compute prime factors of an integer.***

---------------------------------------

<strong>Solution: </strong>

```python
n=int(input("Enter an integer:"))
print("Factors are:")
i=1
while(i<=n):
    k=0
    if(n%i==0):
        j=1
        while(j<=i):
            if(i%j==0):
                k=k+1
            j=j+1
        if(k==2):
            print(i)
    i=i+1
 
 
```
----------------------------------------


# Question 89

### **Question:**

> ***Write a program to generate all the divisors of an integer.***

---------------------------------------

<strong>Solution: </strong>

```python
 
n=int(input("Enter an integer:"))
print("The divisors of the number are:")
for i in range(1,n+1):
    if(n%i==0):
        print(i)
 
```
----------------------------------------

# Question 90

### **Question:**

> ***Write a program to print the table of a given number.***

---------------------------------------

<strong>Solution: </strong>

```python
 
n=int(input("Enter the number to print the tables for:"))
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
    print("The number is an armstrong number. ")
else:
    print("The number isn't an arsmtrong number. ")
 
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

> ***Write a program to check if a number is a Perfect number.***

---------------------------------------

<strong>Solution: </strong>

```python
 
n = int(input("Enter any number: "))
sum1 = 0
for i in range(1, n):
    if(n % i == 0):
        sum1 = sum1 + i
if (sum1 == n):
    print("The number is a Perfect number!")
else:
    print("The number is not a Perfect number!")
 
```
----------------------------------------


# Question 94

### **Question:**

> ***Write a program to find the LCM of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```python
 
a=int(input("Enter the first number:"))
b=int(input("Enter the second number:"))
if(a>b):
    min1=a
else:
    min1=b
while(1):
    if(min1%a==0 and min1%b==0):
        print("LCM is:",min1)
        break
    min1=min1+1
 
```
----------------------------------------


# Question 95

### **Question:**

> ***Write a program to find the GCD of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```python
 
import math
a=int(input("Enter the first number:"))
b=int(input("Enter the second number:"))
print("The GCD of the two numbers is",math.gcd(a,b))
 
```
----------------------------------------


# Question 96

### **Question:**

> ***Write a program to compute a polynomial equation given that the coefficients of the polynomial are stored in the list.***

---------------------------------------

<strong>Solution: </strong>

```python

import math
print("Enter the coefficients of the form ax^3 + bx^2 + cx + d")
lst=[]
for i in range(0,4):
    a=int(input("Enter coefficient:"))
    lst.append(a)
x=int(input("Enter the value of x:"))
sum1=0
j=3
for i in range(0,3):
    while(j>0):
        sum1=sum1+(lst[i]*math.pow(x,j))
        break
    j=j-1
sum1=sum1+lst[3]
print("The value of the polynomial is:",sum1)
 
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

> ***Write a program to find the sum of sine series.***

---------------------------------------

<strong>Solution: </strong>

```python

import math
def sin(x,n):
    sine = 0
    for i in range(n):
        sign = (-1)**i
        pi=22/7
        y=x*(pi/180)
        sine = sine + ((y**(2.0*i+1))/math.factorial(2*i+1))*sign
    return sine
x=int(input("Enter the value of x in degrees:"))
n=int(input("Enter the number of terms:"))
print(round(sin(x,n),2))

 
```
----------------------------------------

# Question 101

### **Question:**

> ***Write a program to find the sum of cosine series.***

---------------------------------------

<strong>Solution: </strong>

```python

import math
def cosine(x,n):
    cosx = 1
    sign = -1
    for i in range(2, n, 2):
        pi=22/7
        y=x*(pi/180)
        cosx = cosx + (sign*(y**i))/math.factorial(i)
        sign = -sign
    return cosx
x=int(input("Enter the value of x in degrees:"))
n=int(input("Enter the number of terms:"))
print(round(cosine(x,n),2))

 
```
----------------------------------------

# Question 102

### **Question:**

> ***Write a program to find the sum of first N Natural Numbers.***

---------------------------------------

<strong>Solution: </strong>

```python

n=int(input("Enter a number: "))
sum1 = 0
while(n > 0):
    sum1=sum1+n
    n=n-1
print("The sum of first n natural numbers is",sum1)
 
```
----------------------------------------
# Question 103

### **Question:**

> ***Write a program to find the sum of series: 1 + 1/2 + 1/3 + ….. + 1/N.***

---------------------------------------

<strong>Solution: </strong>

```python
n=int(input("Enter the number of terms: "))
sum1=0
for i in range(1,n+1):
    sum1=sum1+(1/i)
print("The sum of series is",round(sum1,2))
 
```
----------------------------------------

# Question 104

### **Question:**

> ***Write a program to determine all Pythagorean triplets till the upper limit.***

---------------------------------------

<strong>Solution: </strong>

```python
limit=int(input("Enter upper limit:"))
c=0
m=2
while(c<limit):
    for n in range(1,m+1):
        a=m*m-n*n
        b=2*m*n
        c=m*m+n*n
        if(c>limit):
            break
        if(a==0 or b==0 or c==0):
            break
        print(a,b,c)
    m=m+1
 
```
----------------------------------------

# Question 105

### **Question:**

> ***Write a program to search the number of times a particular number occurs in a list.***

---------------------------------------

<strong>Solution: </strong>

```python
a=[]
n=int(input("Enter number of elements:"))
for i in range(1,n+1):
    b=int(input("Enter element:"))
    a.append(b)
k=0
num=int(input("Enter the number to be counted:"))
for j in a:
    if(j==num):
        k=k+1
print("Number of times",num,"appears is",k)

 
```
----------------------------------------

# Question 106

### **Question:**

> ***Write a program to test Collatz conjecture for a given number.***

---------------------------------------

<strong>Solution: </strong>

```python
def collatz(n):
    while n > 1:
        print(n, end=' ')
        if (n % 2):
            # n is odd
            n = 3*n + 1
        else:
            # n is even
            n = n//2
    print(1, end='')
 
 
n = int(input('Enter n: '))
print('Sequence: ', end='')
collatz(n)
 
 
```
----------------------------------------


# Question 107

### **Question:**

> ***Write a program to count set bits in a number.***

---------------------------------------

<strong>Solution: </strong>

```python
 
def count_set_bits(n):
    count = 0
    while n:
        n &= n - 1
        count += 1
    return count
 
 
n = int(input('Enter n: '))
print('Number of set bits:', count_set_bits(n))
 
```
----------------------------------------

# Question 108

### **Question:**

> ***Write a program to find whether a number is a power of two.***

---------------------------------------

<strong>Solution: </strong>

```python
 
def is_power_of_two(n):
    """Return True if n is a power of two."""
    if n <= 0:
        return False
    else:
        return n & (n - 1) == 0
 
 
n = int(input('Enter a number: '))
 
if is_power_of_two(n):
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
string=input("Enter string:")
string=string.replace('a','$')
string=string.replace('A','$')
print("Modified string:")
print(string)
 
```
----------------------------------------

# Question 114

### **Question:**

> ***Write a program to remove the n<sup>th</sup> index character from a non-empty string.***

---------------------------------------

<strong>Solution: </strong>

```python
def remove(string, n):  
      first = string[:n]   
      last = string[n+1:]  
      return first + last
string=input("Enter the string:")
n=int(input("Enter the index of the character to remove:"))
print("Modified string:")
print(remove(string, n))
 
```
----------------------------------------

# Question 115

### **Question:**

> ***Write a program to detect if two strings are anagrams.***

---------------------------------------

<strong>Solution: </strong>

```python
s1=input("Enter first string:")
s2=input("Enter second string:")
if(sorted(s1)==sorted(s2)):
      print("The strings are anagrams.")
else:
      print("The strings aren't anagrams.")

 
```
----------------------------------------

# Question 116

### **Question:**

> ***Write a program to form a string where the first character and the last character have been exchanged.***

---------------------------------------

<strong>Solution: </strong>

```python
def change(string):
      return string[-1:] + string[1:-1] + string[:1]
string=input("Enter string:")
print("Modified string:")
print(change(string))
 
 
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
 
string=input("Enter string:")
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
 
string=input("Enter string:")
count=0
for i in string:
      count=count+1
print("Length of the string is:")
print(count)
 
```
----------------------------------------


# Question 120

### **Question:**

> ***Write a program to remove the characters of odd index values in a string.***

---------------------------------------

<strong>Solution: </strong>

```python

def modify(string):  
  final = ""   
  for i in range(len(string)):  
    if i % 2 == 0:  
      final = final + string[i]  
  return final
string=input("Enter string:")
print("Modified string is:")
print(modify(string))
 
```
----------------------------------------


# Question 121

### **Question:**

> ***Write a program to calculate the number of words and characters present in a string.***

---------------------------------------

<strong>Solution: </strong>

```python
 
string=input("Enter string:")
char=0
word=1
for i in string:
      char=char+1
      if(i==' '):
            word=word+1
print("Number of words in the string:")
print(word)
print("Number of characters in the string:")
print(char)
 
```
----------------------------------------


# Question 122

### **Question:**

> ***Write a program to take in two strings and display the larger string without using built-in functions.***

---------------------------------------

<strong>Solution: </strong>

```python
 
string1=input("Enter first string:")
string2=input("Enter second string:")
count1=0
count2=0
for i in string1:
      count1=count1+1
for j in string2:
      count2=count2+1
if(count1<count2):
      print("Larger string is:")
      print(string2)
elif(count1==count2):
      print("Both strings are equal.")
else:
      print("Larger string is:")
      print(string1)
 
```
----------------------------------------


# Question 123

### **Question:**

> ***Write a program to count number of lowercase characters in a string.***

---------------------------------------

<strong>Solution: </strong>

```python
 
string=input("Enter string:")
count=0
for i in string:
      if(i.islower()):
            count=count+1
print("The number of lowercase characters is:")
print(count)
 
```
----------------------------------------


# Question 124

### **Question:**

> ***Write a program to count the number of lowercase letters and uppercase letters in a string.***

---------------------------------------

<strong>Solution: </strong>

```python

string=input("Enter string:")
count1=0
count2=0
for i in string:
      if(i.islower()):
            count1=count1+1
      elif(i.isupper()):
            count2=count2+1
print("The number of lowercase characters is:")
print(count1)
print("The number of uppercase characters is:")
print(count2)
 
```
----------------------------------------


# Question 125

### **Question:**

> ***Write a program to calculate the number of digits and letters in a string.***

---------------------------------------

<strong>Solution: </strong>

```python

string=input("Enter string:")
count1=0
count2=0
for i in string:
      if(i.isdigit()):
            count1=count1+1
      count2=count2+1
print("The number of digits is:")
print(count1)
print("The number of characters is:")
print(count2)
 
```
----------------------------------------


# Question 126

### **Question:**

> ***Write a program to form a new string made of the first 2 characters and last 2 characters from a given string.***

---------------------------------------

<strong>Solution: </strong>

```python

string=input("Enter string:")
count=0
for i in string:
      count=count+1
new=string[0:2]+string[count-2:count]
print("Newly formed string is:")
print(new)
 
```
----------------------------------------


# Question 127

### **Question:**

> ***Write a program to count the occurrences of each word in a given string sentence.***

---------------------------------------

<strong>Solution: </strong>

```python

string=input("Enter string:")
word=input("Enter word:")
a=[]
count=0
a=string.split(" ")
for i in range(0,len(a)):
      if(word==a[i]):
            count=count+1
print("Count of the word is:")
print(count)

 
```
----------------------------------------


# Question 128

### **Question:**

> ***Write a program to check if a substring is present in a given string.***

---------------------------------------

<strong>Solution: </strong>

```python

string=input("Enter string:")
sub_str=input("Enter word:")
if(string.find(sub_str)==-1):
      print("Substring not found in string!")
else:
      print("Substring in string!")

 
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

> ***Write a program to add a key-value pair to a dictionary.***

---------------------------------------

<strong>Solution: </strong>

```python
key=int(input("Enter the key (int) to be added:"))
value=int(input("Enter the value for the key to be added:"))
d={}
d.update({key:value})
print("Updated dictionary is:")
print(d)
 
```
----------------------------------------

# Question 132

### **Question:**

> ***Write a program to concatenate two dictionaries into one dictionary.***

---------------------------------------

<strong>Solution: </strong>

```python
d1={'A':1,'B':2}
d2={'C':3}
d1.update(d2)
print("Concatenated dictionary is:")
print(d1)
 
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
print("Total sum of values in the dictionary:")
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
tot=1
for i in d:    
    tot=tot*d[i]
print(tot)
 
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

> ***Write a program to form a dictionary from an object of a class.***

---------------------------------------

<strong>Solution: </strong>

```python
 
class A(object):  
     def __init__(self):  
         self.A=1  
         self.B=2  
obj=A()  
print(obj.__dict__)
 
```
----------------------------------------


# Question 138

### **Question:**

> ***Write a program to map two lists into a dictionary.***

---------------------------------------

<strong>Solution: </strong>

```python

keys=[]
values=[]
n=int(input("Enter number of elements for dictionary:"))
print("For keys:")
for x in range(0,n):
    element=int(input("Enter element" + str(x+1) + ":"))
    keys.append(element)
print("For values:")
for x in range(0,n):
    element=int(input("Enter element" + str(x+1) + ":"))
    values.append(element)
d=dict(zip(keys,values))
print("The dictionary is:")
print(d)
 
```
----------------------------------------


# Question 139

### **Question:**

> ***Write a program to count the frequency of words appearing in a string using a dictionary.***

---------------------------------------

<strong>Solution: </strong>

```python
 
test_string=input("Enter string:")
l=[]
l=test_string.split()
wordfreq=[l.count(p) for p in l]
print(dict(zip(l,wordfreq)))
 
```
----------------------------------------


# Question 140

### **Question:**

> ***Write a program to create a dictionary with key as first character and value as words starting with that character.***

---------------------------------------

<strong>Solution: </strong>

```python
 
test_string=input("Enter string:")
l=test_string.split()
d={}
for word in l:
    if(word[0] not in d.keys()):
        d[word[0]]=[]
        d[word[0]].append(word)
    else:
        if(word not in d[word[0]]):
          d[word[0]].append(word)
for k,v in d.items():
        print(k,":",v)
 
```
----------------------------------------


# Question 141

### **Question:**

> ***Write a program to count the number of vowels present in a string using sets.***

---------------------------------------

<strong>Solution: </strong>

```python
 
s=input("Enter string:")
count = 0
vowels = set("aeiou")
for letter in s:
    if letter in vowels:
        count += 1
print("Count of the vowels is:")
print(count)
 
```
----------------------------------------


# Question 142

### **Question:**

> ***Write a program to check common letters in the two input strings.***

---------------------------------------

<strong>Solution: </strong>

```python

s1=input("Enter first string:")
s2=input("Enter second string:")
a=list(set(s1)&set(s2))
print("The common letters are:")
for i in a:
    print(i)
 
```
----------------------------------------


# Question 143

### **Question:**

> ***Write a program to display which letters are in the first string but not in the second string.***

---------------------------------------

<strong>Solution: </strong>

```python

s1=input("Enter first string:")
s2=input("Enter second string:")
a=list(set(s1)-set(s2))
print("The letters are:")
for i in a:
    print(i)
 
```
----------------------------------------


# Question 144

### **Question:**

> ***Write a program to display which letters is present in both the strings.***

---------------------------------------

<strong>Solution: </strong>

```python

s1=input("Enter first string:")
s2=input("Enter second string:")
a=list(set(s1)|set(s2))
print("The letters are:")
for i in a:
    print(i)
 
```
----------------------------------------


# Question 145

### **Question:**

> ***Write a program to determine whether a given number is even or odd recursively.***

---------------------------------------

<strong>Solution: </strong>

```python

def check(n):
    if (n < 2):
        return (n % 2 == 0)
    return (check(n - 2))
n=int(input("Enter number:"))
if(check(n)==True):
      print("Number is even!")
else:
      print("Number is odd!")

 
```
----------------------------------------


# Question 146

### **Question:**

> ***Write a program to determine how many times a given letter occurs in a string recursively.***

---------------------------------------

<strong>Solution: </strong>

```python

def check(string,ch):
      if not string:
        return 0
      elif string[0]==ch:
            return 1+check(string[1:],ch)
      else:
            return check(string[1:],ch)
string=input("Enter string:")
ch=input("Enter character to check:")
print("Count is:")
print(check(string,ch))

 
```
----------------------------------------

# Question 147

### **Question:**

> ***Write a program to find the fibonacci series using recursion.***

---------------------------------------

<strong>Solution: </strong>

```python

def fibonacci(n):
    if(n <= 1):
        return n
    else:
        return(fibonacci(n-1) + fibonacci(n-2))
n = int(input("Enter number of terms:"))
print("Fibonacci sequence:")
for i in range(n):
    print (fibonacci(i))

 
```
----------------------------------------

# Question 148

### **Question:**

> ***Write a program to find the factorial of a number using recursion.***

---------------------------------------

<strong>Solution: </strong>

```python

def factorial(n):
    if(n <= 1):
        return 1
    else:
        return(n*factorial(n-1))
n = int(input("Enter number:"))
print("Factorial:")
print(factorial(n))
 
```
----------------------------------------
# Question 149

### **Question:**

> ***Write a program to find the sum of elements in a list recursively.***

---------------------------------------

<strong>Solution: </strong>

```python
def sum_arr(arr,size):
   if (size == 0):
     return 0
   else:
     return arr[size-1] + sum_arr(arr,size-1)
n=int(input("Enter the number of elements for list:"))
a=[]
for i in range(0,n):
    element=int(input("Enter element:"))
    a.append(element)
print("The list is:")
print(a)
print("Sum of items in list:")
b=sum_arr(a,n)
print(b)
 
```
----------------------------------------

# Question 150

### **Question:**

> ***Write a program to find the binary equivalent of a number recursively.***

---------------------------------------

<strong>Solution: </strong>

```python
l=[]
def convert(b):
    if(b==0):
        return l
    dig=b%2
    l.append(dig)
    convert(b//2)
a=int(input("Enter a number: "))
convert(a)
l.reverse()
print("Binary equivalent:")
for i in l:
    print (i)
 
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

s = "abcdefghijklmnopqrstuvwxyz01234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ!@#$%^&*()?"
passlen = 8
p =  "".join(random.sample(s,passlen ))
print (p)
 
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

> ***Write a program to count the number of CPUs being used. ***

---------------------------------------

<strong>Solution: </strong>

```python
 
import multiprocessing
print(multiprocessing.cpu_count())
 
```
----------------------------------------


# Question 177

### **Question:**

> ***Write a program to remove punctuations from a string.***

---------------------------------------

<strong>Solution: </strong>

```python
 
# define punctuation
punctuations = '''!()-[]{};:'"\,<>./?@#$%^&*_~'''

my_str = "Hello!!!, he said ---and went."

# To take input from the user
# my_str = input("Enter a string: ")

# remove punctuation from the string
no_punct = ""
for char in my_str:
   if char not in punctuations:
       no_punct = no_punct + char

# display the unpunctuated string
print(no_punct)
 
```
----------------------------------------


# Question 178

### **Question:**

> ***Write a program to find the hash of a file and display it.***

---------------------------------------

<strong>Solution: </strong>

```python

import hashlib

def hash_file(filename):
   """"This function returns the SHA-1 hash
   of the file passed into it"""

   # make a hash object
   h = hashlib.sha1()

   # open file for reading in binary mode
   with open(filename,'rb') as file:

       # loop till the end of the file
       chunk = 0
       while chunk != b'':
           # read only 1024 bytes at a time
           chunk = file.read(1024)
           h.update(chunk)

   # return the hex representation of digest
   return h.hexdigest()

message = hash_file("languages.txt")
print(message)
 
```
----------------------------------------


# Question 179

### **Question:**

> ***Write a program to find the size (resolution) of a image.***

---------------------------------------

<strong>Solution: </strong>

```python

def jpeg_res(filename):
   """"This function prints the resolution of the jpeg image file passed into it"""

   # open image for reading in binary mode
   with open(filename,'rb') as img_file:

       # height of image (in 2 bytes) is at 164th position
       img_file.seek(163)

       # read the 2 bytes
       a = img_file.read(2)

       # calculate height
       height = (a[0] << 8) + a[1]

       # next 2 bytes is width
       a = img_file.read(2)

       # calculate width
       width = (a[0] << 8) + a[1]

   print("The resolution of the image is",width,"x",height)

jpeg_res("img1.jpg")
 
```
----------------------------------------


# Question 180

### **Question:**

> ***Write a program to read website source code.***

---------------------------------------

<strong>Solution: </strong>

```python
import sys

if sys.version_info[0] == 3:
    from urllib.request import urlopen
else:
    # Not Python 3 - today, it is most likely to be Python 2
    # But note that this might need an update when Python 4
    # might be around one day
    from urllib import urlopen


# Your code where you can use urlopen
with urlopen("http://www.myw3schools.com") as url:
    s = url.read()

print(s)
```
----------------------------------------


# Question 181

### **Question:**

> ***Write a program to get IP address of your computer.***

---------------------------------------

<strong>Solution: </strong>

```python
import socket    
hostname = socket.gethostname()    
IPAddr = socket.gethostbyname(hostname)    
print("Your Computer Name is:" + hostname)    
print("Your Computer IP Address is:" + IPAddr) 
```
----------------------------------------

# Question 182

### **Question:**

> ***Write a program to get all links from a webpage.***

---------------------------------------

<strong>Solution: </strong>

```python
from bs4 import BeautifulSoup
from urllib.request import Request, urlopen

req = Request("http://www.myw3schools.com")
html_page = urlopen(req)

soup = BeautifulSoup(html_page, "lxml")

links = []
for link in soup.findAll('a'):
    links.append(link.get('href'))

print(links)
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
number = int(input("Enter an integer: "))
if(number%5==0):
    print(number, "is a multile of 5")
else:
    print(number, "is not a multiple of 5")
```
----------------------------------------

# Question 186

### **Question:**

> ***Write a program to check whether the given integer is a multiple of both 3 and 5.***

---------------------------------------

<strong>Solution: </strong>

```python
number = int(input("Enter an integer: "))
if((number%3==0)and(number%5==0)):
    print(number, "is a multiple of both 3 and 5")
else:
    print(number, "is not a multiple of both 3 and 5")
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
def print_till_zero(n):
    if (n==0):
        return
    print(n)
    n=n-1
    print_till_zero(n)
print_till_zero(9)
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

> ***Write a program to design a calculator.***

---------------------------------------

<strong>Solution: </strong>

```python
def add(x,y):
    print(x,"+",y,"=", x+y)
def subtract(x,y):
    print(x,"-",y,"=", x-y)
def multiply(x,y):
    print(x,"*",y,"=", x*y)
def divide(x,y):
    print(x,"/",y,"=", x/y)
print("Enter a number:")
n1=input()
print("Enter a number:")
n2=input()
print("Enter the operation +,-,*,/ ") 
op=input() 
if op=='+':
    add(int(n1),int(n2))
elif op=='-':
    subtract(int(n1),int(n2))
elif op=='*':
    multiply(int(n1),int(n2))
elif op=='/':
    divide(int(n1),int(n2))
else:
    print("Invalid entry.")
```
----------------------------------------

# Question 192

### **Question:**

> ***Write a program to find the Maximum of two numbers.***

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

> ***Write a program to find the Minimum of two numbers.***

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

> ***Write a program to Calculate Profit or Loss.***

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

> ***Write a program to Print Even Numbers from 1 to N.***

---------------------------------------

<strong>Solution: </strong>

```python
max = int(input(" Enter the Value of N : "))

for num in range(1, max+1):
    if(num % 2 == 0):
        print("{0}".format(num))
```
----------------------------------------

# Question 197

### **Question:**

> ***Write a program to Print Odd Numbers from 1 to N.***

---------------------------------------

<strong>Solution: </strong>

```python
max = int(input(" Enter the Value of N : "))

for num in range(1, max+1):
    if(num % 2 != 0):
        print("{0}".format(num))
```
----------------------------------------

# Question 198

### **Question:**

> ***Write a program to Compute Sum of Even Numbers from 1 to N.***

---------------------------------------

<strong>Solution: </strong>

```python
max = int(input(" Enter the Value of N : "))
total = 0

for num in range(1, max+1):
    if(num % 2 == 0):
        print("{0}".format(num))
        total = total + num

print("The Sum of Even Numbers from 1 to {0} = {1}".format(num, total))
```
----------------------------------------


# Question 199

### **Question:**

> ***Write a program to Compute Sum of Odd Numbers from 1 to N.***

---------------------------------------

<strong>Solution: </strong>

```python
max = int(input(" Enter the Value of N : "))
total = 0

for num in range(1, max+1):
    if(num % 2 != 0):
        print("{0}".format(num))
        total = total + num

print("The Sum of Odd Numbers from 1 to {0} = {1}".format(num, total))
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

> ***Write a program to Convert String to Uppercase.***

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

> ***Write a program to Convert String to Lowercase.***

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

> ***Write a program to Convert Decimal to Binary, octal, and Hexadecimal.***

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

> ***Write a program to print the Number of seconds in Year.***

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




