
# Python Variables



Variables are containers for storing data values.

----------

Creating Variables

Python has no command for declaring a variable.

A variable is created the moment you first assign a value to it.

- Example:
```
x = 5y = "John"  
print(x)  
print(y)
```
Variables do not need to be declared with any particular _type_, and can even change type after they have been set.

- Example:
```
x = 4  # x is of type int  
x = "Sally"  # x is now of type str  
print(x)
```
### Casting

If you want to specify the data type of a variable, this can be done with casting.

- Example:
```

x = str(3) # x will be '3'  
y = int(3) # y will be 3  
z = float(3) # z will be 3.0
```

### Get the Type

You can get the data type of a variable with the type() function.

- Example
```
x = 5y = "John"  
print(type(x))  
print(type(y))
```

# Python - Variable Names

### Variable Names

A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:

-   A variable name must start with a letter or the underscore character
-   A variable name cannot start with a number
-   A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
-   Variable names are case-sensitive (age, Age and AGE are three different variables)

### Example

Legal variable names:
```

myvar = "John"
my_var = "John"
_my_var = "John"
myVar = "John"
MYVAR = "John"
myvar2 = "John"
```

### Multi Words Variable Names

Variable names with more than one word can be difficult to read.

There are several techniques you can use to make them more readable:

### Camel Case

Each word, except the first, starts with a capital letter:
```
myVariableName = "John"
```

----------

### Pascal Case

Each word starts with a capital letter:

```
MyVariableName = "John"
```


----------

### Snake Case

Each word is separated by an underscore character:
```
my_variable_name = "John"
```

# Python - Global Variables

### Global Variables

Variables that are created outside of a function (as in all of the examples above) are known as global variables.

Global variables can be used by everyone, both inside of functions and outside.

- Example:

Create a variable outside of a function, and use it inside the function
```
x = "awesome"  
  
def myfunc():print("Python is " + x)  
  
myfunc()
```

If you create a variable with the same name inside a function, this variable will be local, and can only be used inside the function. The global variable with the same name will remain as it was, global and with the original value.

- Example:

Create a variable inside a function, with the same name as the global variable

```
x = "awesome"  
  
def myfunc():x = "fantastic"  
print("Python is " + x)  
  
myfunc()  
  
print("Python is " + x)
```

### The global Keyword

Normally, when you create a variable inside a function, that variable is local, and can only be used inside that function.

To create a global variable inside a function, you can use the global keyword.

- Example:

If you use the global keyword, the variable belongs to the global scope:

```
def myfunc():global x  
x = "fantastic"  
  
myfunc()  
  
print("Python is " + x)
```

Also, use the global keyword if you want to change a global variable inside a function.

- Example

To change the value of a global variable inside a function, refer to the variable by using the global keyword:
```

x = "awesome"  
  
def myfunc():global x  
x = "fantastic"  
  
myfunc()  
  
print("Python is " + x)```

