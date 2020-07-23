```python
print("Hello \")
```


      File "<ipython-input-1-646ae8df4860>", line 1
        print("Hello \")
                        ^
    SyntaxError: EOL while scanning string literal
    



```python
 print ("hello 
        python")
```


      File "<ipython-input-2-88dd90e972e9>", line 1
        print ("hello
                      ^
    SyntaxError: EOL while scanning string literal
    



```python
 print("hello \
 python")
```

    hello python
    


```python
print("""iam funny""")
```

    iam funny
    


```python
""" iam serious"""
```




    ' iam serious'




```python
print(" the statement in the 5 column is doc string \
created by using triple quotes")
```

     the statement in the 5 column is doc string created by using triple quotes
    


```python
print ("the satatement in the 3 column is an example of blackslash used for continuing with the line")
```

    the satatement in the 3 column is an example of blackslash used for continuing with the line
    
#NOW WE WILL LEARN ABOUT STRING INSIDE THE QUOTE

```python
##NOW WE WILL LEARN ABOUT STRING INSIDE THE QUOTE
```


```python
#NOW WE WILL LEARN ABOUT STRING INSIDE THE QUOTE
```


```python
# NOW WE WILL LEARN ABOUT STRING INSIDE THE QUOTE
```

# NOW WE WILL LEARN ABOUT STRING INSIDE THE QUOTE


```python
print(" hello world")
```

     hello world
    


```python
print('hello world')
```

    hello world
    


```python
print('python's world')
```


      File "<ipython-input-13-3f3d487a621e>", line 1
        print('python's world')
                      ^
    SyntaxError: invalid syntax
    


As you can see when we are using string within string it is showing an syntex error

So while writing quote within quote first use a double and then use a single quote


```python
print("hello in python's world")
```

    hello in python's world
    


```python
print(""" hello " in the python's world" """)
```

     hello " in the python's world" 
    

Now by writing triple quote we have ascertained that whatever we will write in them should be shown as output as it is.That is why it is showing double quotes as it is. And in the inner loop double quotes are ensuring the same, so its loop within loop.

# NOW WE WILL LEARN ESCAPE SEQUENCE OF STRING

It can be use to create spaces in between the words.


```python
print("hello\tpython")
```

    hello	python
    

Here you have to write t which represent tab

Also it can be use to create a new line or it is same as enter. The output will be shown in line one below other.


```python
print("hello\npython")
```

    hello
    python
    


```python
print("hello\ npython")
```

    hello\ npython
    


```python
print("hello \npython")
```

    hello 
    python
    

So note down in the 18 and 19 column there should be no gap or space between blackslash and the syntex following it

Also now we have seen use of blackslash and of string inside the quote. Now we will show mix example of them.

# Blackslash + String inside the quote


```python
print('welcome in python \'s world')
```

    welcome in python 's world
    

So here we used single quote and by using backslash we can continue with the same line.


```python
print(' hello and welcome in python \'s world its our \'s pleasure')
```

     hello and welcome in python 's world its our 's pleasure
    

Thus without using double quotes and all we can use single quotes and backslash


```python
print('python \a world')
```

    python  world
    

# Now we will learn about formated output

It is used to write multiple line


```python
name = "XYZ"
marks = 90.964852
age = 20
print("The name of person is ", name, "marks is", marks, "age is", age)
```

    The name of person is  XYZ marks is 90.964852 age is 20
    

Thus by defining the variables and using commas in the print statement we can use multiple statements.

As we can see there are many commas and we need to define variables. So we can use formatted statement for the same purpose


```python
print("The name of the person is %s marks is %f age is %d"%(name,marks,age))
```


```python
print("The name of the person is %s marks is %f age is %d"%(name,marks,age))
```

    The name of the person is XYZ marks is 90.964000 age is 20
    


```python
print ("hello world")
```

    hello world
    

As you can see after defining the variable one can use %s = string, %f = float, %d = integer
After writing that one should define is bracket what % means in proper relative manner, for Ex. %(name,marks,age) and then should run the code.

Benefit of using later one is that :
1 One can give spaces in between the connecting line, for Ex. the name of the person is XYZ            marks is 90            age is 20. Like this. 
This can de done by writing %10s , %10f ets.


```python
print("The name of the person is %10s marks is %10f age is %10d"%(name,marks,age))
```

    The name of the person is        XYZ marks is  90.964000 age is         20
    


```python
print("The name of the person is %5s marks is %5f age is %5d"%(name,marks,age))
```

    The name of the person is   XYZ marks is 90.964000 age is    20
    

Note that here the no. 10, 5 etc represents the no of times (X5 or 10) you require the space.


```python
print("The name of the person is %20s marks is %20f age is %20d"%(name,marks,age))
```

    The name of the person is                  XYZ marks is            90.964000 age is                   20
    

2 The other benefit is that it can be used to write precisely or accurately.Like if marks are 90.3698754 and want only upto 2 decimal places i can write %10.2f or for 3 decimal places %10.3


```python
print("The name of the person is %s marks is %10.3f age is %d"%(name,marks,age))
```

    The name of the person is XYZ marks is     90.965 age is 20
    


```python
print("The name of the person is %s marks is %10.5f age is %d"%(name,marks,age))
```

    The name of the person is XYZ marks is   90.96485 age is 20
    

 Note if a person don't want to use above way one can use f string for writing the same.


```python
print(f"The name of the person is {name} the marks is {90.96} age is {age}")
```

    The name of the person is XYZ the marks is 90.96 age is 20
    


```python
print(f"The name of the person is {name} the marks is {marks} age is {age}")
```

    The name of the person is XYZ the marks is 90.964852 age is 20
    

Note that here you have to use curly brackets.

# PYTHON VARIABLES & ASSIGNMENT STATEMENT

1 Variables means linking of the data to a name 
2 According to the data type, the interpreter reserves the memory space
3 It refers to memory location that contains data

Ex x = name; a = surname etc.


```python
print("""Rules to define a variable""")
```

    Rules to define a variable
    

A keyword cann't be used as a variable. The reserved keywords are "if", "def" and "for".

A variable can contain letters, numbers, underscore. Python is case sensitive and hence variables are also case sensitive.

A variable cann't start with a number. For Ex. 10a is not a variable where as a10 can be a one.

A variable can be used to assign value/data only with the help of assignment operator (=).


```python
x=20
id(x)
```




    140717663101936



Note here we can find the RAM address to which our data has been assigned. For this purpose id() function is used. The output will be the RAM address


```python
y=20
id(y)
```




    140717663101936



Thus look that it gives the same result. It is because the interpreter checks whether the data value is same or not in the memory.


```python
del x
```


```python
y
```




    20



Now note that after deleting x, the memory still has 20 pointed by y and that is why it is still showing 20

Deletion means deleting the binding between x and 20 and not the value


```python
del y
```

Now here both the variables pointing to 20 has been deleted and in the memory there is no other variable pointing towards 20 then the interpreter automatically deletes 20 from the memory

# DIFFERENT TYPES OF PYTHON OPERATORS

Airthmetic,
Comparision,
Assignment,
Bitwise,
Logical,
Membership,
Identity,

1 Airthmetic


```python
5*5
```




    25




```python
5**6
```




    15625




```python
10+20
```




    30




```python
25/3
```


```python
12+2
```


```python
25/3
```




    8.333333333333334



Now here you can see that in python after dividing operation you get a float value


```python
25%3
```




    1



Here % is the modulus operator that gives you the reminder of the dividion. i.e an integer value


```python
25//3
```




    8



Now observe the 48 column you can see that single division gives the float value, but when you perform // ie floor division then the result is converted into lowest integer form, i.e. 8. Here the highest integer value will be 9.


```python
a = 10
b = 20
a ==b
```




    False




```python
a > b
```




    False




```python
a < b
```




    True




```python
c = 20
```


```python
a <= c
```




    True




```python
a >= c
```




    False




```python
a != c
```




    True




```python
b != c
```




    False




```python
a == b
```




    False




```python
a == c
```




    False




```python
b == c
```




    True




```python
a = b
```


```python
a += b
```


```python
a = b
```


```python
a += b
```


```python
a=240
b=1
a|b
```




    241




```python
bin(a)
```




    '0b11110000'




```python
bin(b)
```




    '0b1'




```python
a & b
```




    0




```python
a = 1
b =10
a > 20 or b > 9
```




    True




```python
10>9 and 20>M
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-71-9b6b05d7a0cf> in <module>
    ----> 1 10>9 and 20>M
    

    NameError: name 'M' is not defined



```python
10<9 and 20>M
```




    False




```python
print(" Shree Swami Samarth")
```

     Shree Swami Samarth
    

# Shree Swami Samarth


```python
10<9
```




    False




```python
not 10<9
```




    True



Here not is the inverter that invert the output


```python
10>9 & 1<10
```




    True




```python
not 10>9 & 1<10
```




    False




```python
not true
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-78-e1c80afc9194> in <module>
    ----> 1 not true
    

    NameError: name 'true' is not defined



```python
strl = "pythonprogramming"
"a" in strl
```




    True



Here the membership operator "in" checks the presence of of "a" in strl


```python
A = "Deepashri"
"e" in A
```




    True




```python
"z" not in strl
```




    True




```python
"a" not in strl
```




    False



Here the "not in" operator checks the absence of z in strl


```python
a=10
b=20
a==b
```




    False




```python
a=10
b=10
a==b
```




    True




```python
id(a)
```




    140717663101616




```python
id(b)
```




    140717663101616




```python
a is b
```




    True




```python
a is not b
```




    False




```python
c=25
a is not c
```




    True



Here identity operators "is" and "is not" tells whether the two variables have same memory location or not.


```python
a= 4
b=4
a is b
```




    True




```python
a=257
b=257
a==b
```




    True




```python
a is b
```




    False



It is because for integer -5 to 256 is assigned same memory location and after that different locations are given.


```python
 10/20*4**2
```




    8.0




```python
10+10/20*4
```




    12.0




```python
10+10/29*4
```




    11.379310344827587




```python
2**-1
```




    0.5




```python
a=-6
b=-6
a is b
```




    False




```python
id(-6)
```




    861147960944




```python
id(b)
```




    861147961168



So see that it allots different address


```python
10>8>9
```




    False




```python
10>8 & 8>9
```




    False



# THANK YOU


```python

```
