
# Python Dictionaries


Dictionaries are used to store data values in key:value pairs.

A dictionary is a collection which is ordered*, changeable and do not allow duplicates.

As of Python version 3.7, dictionaries are _ordered_. In Python 3.6 and earlier, dictionaries are _unordered_.

Dictionaries are written with curly brackets, and have keys and values:

- Example

Create and print a dictionary:


```
thisdict =  {  
"brand": "Ford",  
"model": "Mustang",  
"year": 1964  
}  
print(thisdict)  
```


----------

### Dictionary Items

Dictionary items are ordered, changeable, and does not allow duplicates.

Dictionary items are presented in key:value pairs, and can be referred to by using the key name.

- Example

Print the "brand" value of the dictionary:

```
thisdict =  {  
"brand": "Ford",  
"model": "Mustang",  
"year": 1964  
}  
print(thisdict["brand"]) 
 ```



----------

### Ordered or Unordered?

As of Python version 3.7, dictionaries are _ordered_. In Python 3.6 and earlier, dictionaries are _unordered_.

When we say that dictionaries are ordered, it means that the items have a defined order, and that order will not change.

Unordered means that the items does not have a defined order, you cannot refer to an item by using an index.

----------

### Changeable

Dictionaries are changeable, meaning that we can change, add or remove items after the dictionary has been created.

----------

### Duplicates Not Allowed

Dictionaries cannot have two items with the same key:

- Example

Duplicate values will overwrite existing values:

```
thisdict =  {  
"brand": "Ford",  
"model": "Mustang",  
"year": 1964,  
"year": 2020  
}  
print(thisdict)
```

----------

### Dictionary Length

To determine how many items a dictionary has, use the len() function:

- Example

Print the number of items in the dictionary:

```
print(len(thisdict))
```

----------

### Dictionary Items - Data Types

The values in dictionary items can be of any data type:

- Example

String, int, boolean, and list data types:

```
thisdict =  {  
"brand": "Ford",  
"electric": False,  
"year": 1964,  
"colors": ["red", "white", "blue"]  
}
```

----------

### type()

From Python's perspective, dictionaries are defined as objects with the data type 'dict':

<class 'dict'>

- Example

Print the data type of a dictionary:

```
thisdict =  {  
"brand": "Ford",  
"model": "Mustang",  
"year": 1964  
}  
print(type(thisdict))
```

