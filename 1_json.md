# JSON and data structures.

Before we can start coding we need to learn how computers think about data. Whilst we know that computers use 1 & 0 simple binary, programming languages provide us with easy to use data *types*.

A *variable* is a thing that we can create on the fly to store a piece of data. A variable has a *type*.

We need to understand the following *types* of *variable* before we can move forward.

## String 

A string is a sequence of characters wrapped in quotes. "Meow", "Woof", "Quack", "1234". A number becomes a string if it's inside quotes.

```python
>>> mystring = "Quack"
>>> type(mystring)
<class 'str'>
```

## Integer

An integer is a whole number such as 1, 2, 3 or 2048.

```python
>>> myinteger = 10
>>> type(myinteger)
<class 'int'>
```

## Floating point number

Floating point number are decimal numbers such as 0.2, 1/5 or 455.22333. We call them "floating point" because it is not possible for a computer to store a true decimal number or fraction.

```python
>>> myfloat = 10.1
>>> type(myfloat)
<class 'float'>
```

## Booleans

Booleans can either be true or false.

```python
>>> mybool = True
>>> type(mybool)
<class 'bool'>
```

# List

A list is a simple sequence of values.

List of Integers: [1, 2, 3, 4]

List of Strings: ["dog", "cat", "mouse", "moose"]

List of Floating Point Numbers: [1.1, 1.2, 1.3, 1.4]

```python
>>> mylist = [1, 2, 3, 4]
>>> type(mylist)
<class 'list'>
```

# Dictionary
A dictionary is a list of *"key"*: "value" pairs.

{*"breed"*: "labrador", *"color"*: "black", *"name"*: "rex"}

{*"breed"*: "spaniel", *"color"*: "brown", *"name"*: "rover"}

```python
>>> mydictionary = {"breed": "labrador", "color": "black", "name": "rex"}  
>>> type(mydictionary)
<class 'dict'>
```