
# Python break and continue

**What is the use of break and continue in Python?**

In Python, break and continue statements can alter the flow of a normal loop.

Loops iterate over a block of code until the test expression is false, but sometimes we wish to terminate the current iteration or even the whole loop without checking test expression.

The break and continue statements are used in these cases.

**Python break statement**

The break statement terminates the loop containing it. Control of the program flows to the statement immediately after the body of the loop.

If the break statement is inside a nested loop (loop inside another loop), the break statement will terminate the innermost loop.

**Syntax of break**

Break
<![endif]-->

**Example: Python break**

# Use of break statement inside the loop


```
for val in  "string":

if val == "i":

break

print(val)

print("The end")
```

**Output**

```
s

t

r

The end
```
<![endif]-->

**Python continue statement**

The continue statement is used to skip the rest of the code inside a loop for the current iteration only. Loop does not terminate but continues on with the next iteration.

**Syntax of Continue**

continue


### Example: Python continue

# Program to show the use of continue statement inside loops


```
for `val` in  "string"`:`
  if val == "i":      
      continue   
  print(val) 
print`(`"The end"`)`
```

**Output**


```
s

t

r

n

g

The end
```

