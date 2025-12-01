Here is complete theory for all the important questions you listed — simple, exam-friendly, and directly writable.


---

✅ THEORY NOTES (WRITE THIS IN EXAM)


---

1] Features of Python

1. Simple & Easy – Syntax is easy to read and understand.


2. Interpreted Language – Code runs line by line, easy to debug.


3. Portable – Same code runs on Windows, Mac, Linux.


4. Object-Oriented – Supports classes, objects, inheritance.


5. Extensible – Can use C/C++ code inside Python.


6. Rich Libraries – Contains powerful libraries (NumPy, Pandas, Matplotlib).


7. Dynamic Typing – No need to declare data type.


8. Free & Open Source




---

2] Data Types in Python

1. int – Whole numbers (10, 50)


2. float – Decimal numbers (3.14)


3. string (str) – Text (“Hello”)


4. bool – True/False


5. list – Ordered, mutable collection


6. tuple – Ordered, immutable collection


7. set – Unordered, no duplicates


8. dictionary (dict) – Key–value pairs


9. None – Represents null value




---

3] Conditional Statements (if-else)

Used to make decisions in program.

if condition:
    statement
elif condition:
    statement
else:
    statement


---

4] List

A list is an ordered, mutable collection of items.

Features:

Uses square brackets []

Allows duplicate values

Supports indexing & slicing


Example:

l = [10, 20, 30]

Common Methods:

append(), insert(), remove(), pop(), sort(), reverse()



---

5] DataFrame (Pandas)

A DataFrame is a 2D labelled data structure (rows & columns).

Features:

Like an Excel table

Allows filtering, grouping, merging

Handles missing data

Uses pandas library


Example:

import pandas as pd
df = pd.DataFrame({"Name":["A","B"], "Marks":[50,60]})


---

6] Mutable vs Immutable Objects

Type	Meaning	Examples

Mutable	Can change after creation	list, dict, set
Immutable	Cannot change after creation	int, float, str, tuple



---

7] Python Libraries

1. NumPy – Numerical calculations, arrays


2. Pandas – DataFrame operations


3. Matplotlib – Visualization


4. Seaborn – Advanced charts


5. Scikit-learn – Machine learning


6. Random – Random numbers


7. Math – Mathematical functions




---

8] Grouping Statement (for, while loop)

For Loop

Used when number of iterations is known.

for i in range(1,6):
    print(i)

While Loop

Used when condition-based looping is required.

while i <= 5:
    print(i)
    i += 1


---

9] Operators

1. Arithmetic: +, -, *, /, %, **


2. Relational: >, <, >=, <=, ==, !=


3. Logical: and, or, not


4. Assignment: =, +=, -=


5. Bitwise: &, |, ^, <<, >>


6. Membership: in, not in


7. Identity: is, is not




---

✅ PRACTICAL THEORY


---

1] Program: Table of any number

n = int(input("Enter number: "))
for i in range(1,11):
    print(n, "x", i, "=", n*i)


---

2] Even or Odd

n = int(input("Enter number: "))
if n % 2 == 0:
    print("Even")
else:
    print("Odd")


---

3] Prime Number Check

n = int(input("Enter number: "))
flag = 0
for i in range(2, n):
    if n % i == 0:
        flag = 1
        break

if flag == 0:
    print("Prime")
else:
    print("Not Prime")


---

4] If-Else Bonus Question

Example:

age = int(input("Enter age: "))
if age >= 18:
    print("Adult")
else:
    print("Minor")


---

5] Positive / Negative / Zero

n = int(input("Enter number: "))
if n > 0:
    print("Positive")
elif n < 0:
    print("Negative")
else:
    print("Zero")


---

6] List Program – Remove Duplicate / Sort

Remove duplicates:

l = [1,2,3,2,1]
l = list(set(l))
print(l)

Sorting:

l = [5,1,3,2]
l.sort()
print(l)


---

7] Mid Term Type Questions

(Theory already covered: lists, loops, dictionary, file handling)


---

8] List Elements

Indexing, slicing, adding, removing elements etc.


---

9] Dictionary Create / Print / Delete / Copy

d = {"name":"Sanket", "age":20}

print(d)
del d["age"]
c = d.copy()
print(c)


---

10] NumPy – 1D Series & Statistical Methods

Creation:

import numpy as np
a = np.array([1,2,3,4])

Statistical Functions:

sum()

mean()

median()

max(), min()

std()

var()


2D Array operations:

a + b
a - b
a * b


---

11] File Handling + Data Cleaning Theory

Steps:

1. Read file → pd.read_csv()


2. Remove duplicates → df.drop_duplicates()


3. Check null values → df.isnull().sum()


4. Remove special characters


5. Standardize date format → pd.to_datetime()


6. Save cleaned file → df.to_csv()




---

12] Visualization (groupby, bar, pie)

Bar Chart:

df.groupby('category').size().plot(kind='bar')

Pie Chart:

df.groupby('category').size().plot(kind='pie')

Used for frequency distribution.


---

✅ DONE!

If you want, I can also give you all programs separately, or make a PDF of notes for quick revision.
