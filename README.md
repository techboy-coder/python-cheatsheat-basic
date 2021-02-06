# Python Basics Cheatsheat 🐍

> Quick Summary: This will help you learn the syntax of python very quickly. 😀

##Printing

```python
print("Hello World") #--> Hello World
# The hastag ("#") is used for comments
```

## Variables and Operations

```python
a=5
b=10
print(a+b) #--> 15
print(a*b) #--> 50
"""
Operations
----------
-Simple: a*b,a/b,a+b, a-b
-Advanced: a**b (a raised to b=a^b), a%b (modular remainder e.g. 9 % 2 = 1; 8 %  = 1)
-Tricks: a+=1, a-=1,...
"""
```

## Loops

### For Loop

```python
for i in range(10):
    print(i**2)
"""
Result:
0
1
4
...
64
81
"""
```

### While Loop

```python
a = 1
while a<100:
    a+=1
    print(a)
"""
Result:
2
3
4
...
97
98
99
"""
```

## Datatypes

```python
dog="Bob" #String
emotions=["happy","sad","hungry","angry"] #list| emotions[0]="happy"; emotions[3]="angry"
age=6.2 #Float
legs=4 #Int
```

## Functions

```python
def bark():
    print("Woof!")
bark() #-->Woof!
```

---

© 2021 - Techboy-Coder - https://github.com/techboy-coder
