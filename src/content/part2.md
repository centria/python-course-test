---
title: 'Part 2 - Terminology'
nav_order: 3
hidden: false
---

## Sentence

_Lause_ (_statement_) is the part of a program that performs an action. Often a sentence refers to a single command.

For example, `print (" Hi! ")` Is a phrase that prints line text,
and `number = 2` is a statement that sets a value for the variable.

The sentence can also be more complex, and there can be other sentences inside.
For example, the following conditional sentence consists of three lines:

```python
if name == "Enter":
    print ("Hi!")
    number = 2
```

In this case, there are two sentences within the conditional sentence.

## Block

_Block_ is a set of consecutive sentences that are at the same level in the program structure. For example, a conditional statement in a block contains statements that are executed when the condition is true.

```python
if ika> 17:
    The block in the # conditional statement begins
    print ("You're an adult!")
    ika = ika + 1
    print ("now a year older ...")
    # block ends

print ("this is in a different block")
```

In Python, a block is expressed by indenting the block code, or sentences, to the same level.

It is worth noting that the "main block" of Python must be indented on the left side of the file:

```python
# this program does not work because the code is not indented
  print ("hey world")
  print ("bad program ...")
```

## Function

_Function_ performs an action. A function can have one or more _parameters_ that indicate exactly what the function should do.

A function is executed when it is _called_, that is, the code contains the name of the function and the parameters given to the function in parentheses. For example, the following code calls the `print` function with the parameter` "this is a parameter" `:

```python
print ("this is a parameter")
```

`Input`, which reads input from the user, is also a function. As a parameter, the function receives a message to be displayed to the user:

```python
name = input ("Tell your name:")
```

In this case, the function _resets_ the value, which means that the value appears in the function call point after the function is executed. The value returned by the `input` function is the text entered by the user as a string. The value returned by a function is often placed as the value of a variable so that the value can be utilized in the program.

## Type

_Type_ means what a value in the code is. For example, in the following code, the type of the variable `name` is a string and the type of the variable` result` is an integer:

```python
name = "Enter"
result = 100
```

The `type` function tells you the type of an expression. For example:

```python
print (type ("Anna"))
print (type (100))
```
