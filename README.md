# Deshika-Python

## Variables

> What is a variable?
> It's something that is able to be changed or adapted.

Definition:
https://dictionary.cambridge.org/dictionary/english/variable 

A variable is a label for something.  This something is variable which means it can change.  

## Primitive types

A variable can be one of the primitive types. 

| Primitive Type| Example | Notes |
| -------------------- |-------------|------------|
| int | 793 | A whole number |
| float | 5.777 | A decimal number |
| bool | false | A boolean which is either true OR false |
| string | "a mango" | Usually with double quotes |
| list | [5, 3, 5, 6] | Use square brackets |
| dict | { 'jack': 4098, 'sjoerd': 4127 } | A comma seperated key-value pair |

There are other primitive types like sets, functions and null but above is the most common I have come across in python.  

## Boolean Operations

Any object can be tested for truth value, for use in an if or while condition or as operand of the Boolean operations below.

| Operation | Result | Notes |
| ------- | ------- | -------- |
| x or y | true if either x is true OR y is true | Only false if x and y are false |
| x and y | true if x is true and y is true | Only true if x and y are true
| not x | Inverts the boolean value | if x is true, then not x is false |

## Conditional Statement

It evaluates the if statement lines to see if it is true, then those lines are run.  
If all expressions are false, the else clause, if present, is executed.

```python
name = "tharanga"
if name = "deshani":
  print("deshani is cool")
elif name = "deshika":
  print("deshika is awesome")
elif name = "tharanga":
  print("tharanga is cool")
else:
  print("I'm not sure who that is, sorry")
```

