1. Introduction to Variables
1.1) What will be the type of the add variable?
a = 10

b = 5.1

add = a + b

a = 10
b = 5.1
add = a + b
print(add)
15.1

```diff
- Wrong.
```

1.2) Is 5 = (3+2)?
z = (3+2)

print(z)
print(z==5)

if z == 5:
    print("YES")
else:
    print("NO")
## answer
#YES
5
True
YES

```diff
+ Correct!
```

1.3) Add 33 in variable a and print the result
a = 3

z = 3
z += 33
print (z)
36

```diff
+ Correct!
```
 
1.4) Convert integer variable a to float and check its type
a = 3

z = 3
print (type(z))

print (type(float(z)))
<class 'int'>
<class 'float'>

```diff
+ Correct!
```

2. Collection of Variables
2.1) Create a list of repeated element (element 2,48 times)
listing = []
for z in range (0, 48):
    listing.append (2)

print (listing)
print (len(listing))
[2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2]
48

```diff
- Wrong.
```

2.2) Replace the second element of the list with "strawberries"
list = ["apple","orange","grapes","watermelon"]

list = ["apple", "orange", "grapes", "watermelon"]

print (list)

list [1] = "strawberries"

print (list)
['apple', 'orange', 'grapes', 'watermelon']
['apple', 'strawberries', 'grapes', 'watermelon']

```diff
+ Correct!
```

2.3) Check length of list
List1 =["a","b","c","d","e"]

List1 = ["a", "b", "c", "d", "e"]
len(List1)
5

```diff
+ Correct!
```

2.4) Create a dictionary with the following information:
brand = Audi

Model = Q2

Year = 1980

dictionary1 = {"Brand": "Audi"}
dictionary2 = {"Model": "Q2"}
dictionary3 = {"Year" : 1980}

print (dictionary1)
print (dictionary2)
print (dictionary3)
{'Brand': 'Audi'}
{'Model': 'Q2'}
{'Year': 1980}

```diff
- Wrong.
```

2.5) Create a set of following elements
1.0, "Hello", 55 , (6,7,8)

set1 = {"Hello", 55, (6,7,8)}

print(set1)
{'Hello', (6, 7, 8), 55}

```diff
+ Correct!
```

3. Data Types and String Manipulation
3.1) Printing your name My_Name = "My name is Jupyter!" Also, check if My_Name is all Caps or not. Use isupper() to check returns True if all the letters are Capitals, False if atleast one letter in in lower case.
HINT: My_Name.isupper()

My_Name = input("Print the Following Name >> ")

print (My_Name.isupper())
False

```diff
- Wrong.
```

3.2) Convert My_Name to all caps. Hint: My_Name.upper().
 
3.3) if int1 = "500", what is the Datatype of int1
integer1 = "500"

print (type(integer1)) 
<class 'str'>

```diff
+ Correct!
```

4. Practice Exercise on Conditional Statement
4.1) if x = 20 and y = 30. Write a python code to check if x is less than y.
x = 20
y = 30

if x < y:
    print(True)
else:
    print(False)

```diff
+ Correct!
```
    
4.2) Check if a is equal to 10, If yes, print "Hello", else print "Good Bye"
a = 56

a = 10

if a == 10:
    print("Hello")
else:
    print("Good Bye")
Hello

```diff
+ Correct!
```

4.3) Check whether a number is even or odd
a = 2020

a = 2020

if a % 2 == 0:
    print("variable a is even")
else:
    print("variable a is odd")

```diff
+ Correct!
```
    
4.4) Check if the word "Data" is present in the sentence "I am a Data Scientist". If found, print "It is present" else print FALSE.
 
4.5) Write python code to check if a number is positive or negative.


5. Practice Exercise on Loops
5.1) Print Data Science 5 times using for loop
for z in range(5):
    print("Data Science")
Data Science
Data Science
Data Science
Data Science
Data Science
Note: Remember to keep the index as one more than what is required. In the above code the indexing is done from 0 to 5 which are 6 places but Python has printed it 5 times.

```diff
+ Correct!
```

5.2) Print all the even numbers from 1 to 20 (both inclusive) using for loop.
for z in range(1, 21):
    if z % 2 == 0:
        print(z)
2
4
6
8
10
12
14
16
18
20

```diff
+ Correct!
```

6. Function
6.1) Define the python function to check whether the number 33 is even or odd
def oddOrEven(x):
    if x % 2 == 0:
        print("variable x is even")
    else:
        print("variable x is odd")


oddOrEven(3)
oddOrEven(4)
oddOrEven(0)
variable x is odd
variable x is even
variable x is even

```diff
+ Correct!
```

```diff
! 13/21
```
