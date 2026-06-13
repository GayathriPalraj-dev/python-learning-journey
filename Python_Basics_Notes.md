# Python Basics Notes and Practice

## 1. Variables

Variables store data.

``` python
name = "Gayathri"
age = 22
print(name, age)
```

------------------------------------------------------------------------

## 2. Data Types

-   int
-   float
-   str
-   bool
-   complex

``` python
a = 10
b = 2.5
c = "Python"
d = True
e = 2+3j
print(type(a), type(b), type(c), type(d), type(e))
```

------------------------------------------------------------------------

## 3. Functions

Reusable block of code.

``` python
def add(a,b):
    return a+b

print(add(10,20))
```

------------------------------------------------------------------------

## 4. Lists

Mutable collection.

``` python
numbers = [10,20,30]
numbers.append(40)
print(numbers)
```

Slicing:

``` python
print(numbers[1:3])
print(numbers[::-1])
```

------------------------------------------------------------------------

## 5. Tuples

Immutable collection.

``` python
data = (10,20,30)
print(data[0])
```

Unpacking:

``` python
a,*b = data
print(a,b)
```

------------------------------------------------------------------------

## 6. Strings

Sequence of characters.

``` python
name = "Python"
print(name.upper())
print(name[::-1])
```

Palindrome:

``` python
text = "madam"
print(text == text[::-1])
```

------------------------------------------------------------------------

## 7. Dictionary

Key-value pairs.

``` python
student = {"name":"Gayathri","age":22}
print(student["name"])
```

Loop:

``` python
for key,value in student.items():
    print(key,value)
```

------------------------------------------------------------------------

## 8. Set

Unique values.

``` python
numbers = {10,20,20,30}
print(numbers)
```

frozenset:

``` python
a = frozenset([1,2,3])
print(a)
```

------------------------------------------------------------------------

## 9. Conditional Statements

``` python
num = int(input("Enter number: "))

if num > 0:
    print("Positive")
elif num < 0:
    print("Negative")
else:
    print("Zero")
```

Leap year:

``` python
year = int(input("Enter year: "))

if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print("Leap Year")
else:
    print("Not Leap Year")
```

------------------------------------------------------------------------

## 10. Loops

For loop:

``` python
for i in range(5):
    print(i)
```

While loop:

``` python
i = 1
while i <= 5:
    print(i)
    i += 1
```

Factorial:

``` python
num = 5
fact = 1
for i in range(1,num+1):
    fact *= i
print(fact)
```

Fibonacci:

``` python
a,b = 0,1
for i in range(7):
    print(a,end=" ")
    a,b = b,a+b
```

Prime:

``` python
num = 7
count = 0

for i in range(1,num+1):
    if num % i == 0:
        count += 1

if count == 2:
    print("Prime")
else:
    print("Not Prime")
```

------------------------------------------------------------------------

## Practice Exercises

1.  Even/Odd
2.  Largest of 3 numbers
3.  Sum of list
4.  Reverse string
5.  Palindrome
6.  Grade calculator
7.  Leap year
8.  Fibonacci
9.  Factorial
10. Prime number
