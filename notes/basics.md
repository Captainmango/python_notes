

### Numbers

"""
Can just write numbers without typing. We can do maths on them without casting i.e. sums and such. Can 
implicitly cast to strings with double quotes (string literal).

floating point numbers are numbers with decimals (7 points of precision)
Type conversion is done by parsing [int, float] very similar usage to Java parse functions

"""

### Strings

"""
Strings are a collection of characters. Can use double and single quotes. Can use normal escape routes 
for characters. i.e. using singles inside doubles or back slash

String concatenation can be done with + sign. Can use casting to cast variables to string with the str() function
can also do operations inside of the str() function as per normal rules. (functon needs to evaluate to a number or castable object)

String splitting is done with the split method. Split takes the character to split on and the max number of splits to complete.

Strings can be subset using slices and follow zero indexing inclusive.

"""

### Booleans

"""
Booleans are truthy or falsey. Comparisons return truthy or falsey. Type matters with comparisons. can also use the 'is' and 'not' keywords
instead of equality operator. None is the null/ nil equivalent in Python and is an object. Unlike Ruby where all values are true, Python
works with zero values being false but empty strings being true. Watch for odd behaviour.

"""

### Lists

"""
Lists follow zero index inclusive and are a collection of items inside of a wrapper that has some properties. They are not enumerable,
but can be used in loops as control structures.

"""


### Dictionaries

"""
Key value pair data structure. Access keys with square brackets or the in keyword. Keys cannot be overwritten once instantiated but values
can. Work like lists in all other respects.

"""

### Functions

"""
instantiated with the def keyword. according to PEP guidelines, we use snake case like Ruby. Arguments go in the brackets. Colon
starts the execution block. USE INDENTS FOR SCOPING.

Default arguments are done with assignment inside the function argument list.

Keyword arguments are done in the function call. This allows us to pass arguments in any order.

infinite arguments are passed in with a star. Like this:
    def test_fun(*foo):
        function stuff:
            print(foo)
        return whatever

N.B. do not use the * inside of the function body.

return and break work the same as Ruby

pass is for if we want to pass from a value and not leave the execution context


"""







