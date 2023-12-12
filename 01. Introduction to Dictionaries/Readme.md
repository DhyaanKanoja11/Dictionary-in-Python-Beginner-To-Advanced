# 01 Introduction To Dictionaries

Welcome To The First Chapter To learn The data type of Dictionaries in Python, let's Start 
##
Dictionaries, also known as associative memories or arrays, are indexed by keys, which can be any immutable type. Strings and numbers can be keys, while tuples can only contain strings, numbers, or tuples. Tuples cannot contain mutable objects, and lists cannot be used as keys due to their modification using index assignments, slice assignments, or methods like append() and extend().
###

## Defining a Dictionary in Python
Dictionaries are Python's implementation of an associative array, consisting of key-value pairs that map each key to its associated value. They are defined by enclosing a list of key-value pairs in curly braces and separating each key from its associated value :-
```python
d = {
    <key>: <value>,
    <key>: <value>,
      .
      .
      .
    <key>: <value>
}
```

Lets map this above snippet: 
