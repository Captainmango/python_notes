## if else statements
"""
Allows us to evaluate what is true and what is false
has the following syntax.

```python

if foo is [boolean]:
    [output]
else:
    [output]

```

allows us to have the ability to do check in code.

if you want multiple conditions to be checked, we can use elif. You would need to supply a condition to elif, but it works the same
way as if. 

N.B. we do not have to include else inside of if statements

can also be done as a one liner like so.

```python

<expression 1> if <condition> else <expression 2>

```

"""

## for/ while loops
"""
### for loops
* good for iterating over an array and working in a contiguous way
* good for working with strings
* good for single ops on each item in an iterable

is written using the following syntax:

```python

for <item> in <iterable>:
    [do stuff]

```

for some more granular control, we can use the range() built in to build a list of indicies

"""

### while loops
* good for working with distinct items
* good for working with objects and classes
* good for multiple operations in an execution context

is written using the following syntax:

```python

while <condition>:
    [do something]
    {increment count or change condition such that it can terminate}

```

N.B. it is very easy to forget the iteration within a while loop. Building in a guard clause at the start of this is a good idea for safety but the best practise way to handle this is to use an iterator and increment the count. This is also useful in debugging as you can print the specific iterator in a sequence.
