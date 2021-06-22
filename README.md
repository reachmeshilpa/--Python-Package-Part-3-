# --Python-Package-Part-3-
Learning by Implementation: Set and Sequence

# Set is an unordered collection of UNIQUE ITEMS
# Values are unique numbers (interger or decimal), are separated by commas and are placed within CURLY braces.
set1 = {4,8,10}
print (set1)
OUTPUT -> {8,10,4}

# UNIQUE means duplicates are removed
set2 = {1,1,2,2,2,3,3,3,3,3,4,5,6,6,7,7,7,7,7,7,7,7,8,9,10}
print (set2)
OUTPUT -> {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}

# to check the CLASS/TYPE of a variable in a set
print (type(variable))
print (type (set2))
OUTPUT -> <class 'set'>

# cannot print any particular element from a set as it is an unordered collection of data, index 2 is not known

# SEQUENCES: string, list, tuple

# STRING is a sequence of unicode characters ?? read more
# within single or double quotes
# For multiline strings use triple quotes (single/double), ‘’’ or “””

# Strings can be indexed then called as subscripted using [] straight braces
# The first character of a string has the index 0

stringVariable = 'This is a string variable' #single quote for a single line
print (stringVariable)
print (stringVariable[0])
OUTPUT -> T

# Slicing of a string variable using Index

print (stringVariable[0:12])
print (stringVariable[:12])
# Both of the above statements produce the same result from 0 till 7 th character which is index 0 to 6, spaces within the string are also calculated or taken into account
OUTPUT -> This is a st

# To print from 12th index to end of the string
print (stringVariable[12:])
OUTPUT -> ring variable

# To print from 12th index to end of the string
print (stringVariable[:0])
OUTPUT -> empty space

# To print from 12th index to end of the string
print (stringVariable[0])
OUTPUT -> T
print (stringVariable[:1])
OUTPUT -> T

# To print from 12th index to end of the string
print (stringVariable[:-1])
OUTPUT -> This is a string variabl

#LIST


