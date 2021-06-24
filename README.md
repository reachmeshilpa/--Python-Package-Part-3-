# --Python-Package-Part-3-
Learning by Implementation: Set and Sequences(SLT)

# Set unordered | unique | {}

# It is an unordered collection of UNIQUE ITEMS
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
#---------------------------------------------------------------------------------------------------
# SEQUENCES: string, list, tuple

# STRING is a sequence of unicode characters ?? read more
# within single or double quotes
# For multiline strings use triple quotes (single/double), ‘’’ or “””

# Strings can be indexed then called as subscripted using [] straight braces
# The first character of a string has the index 0

# Some functions with a string
  
 message = 'codingG Questt' # to count the **full length** print(len(variable)) of the value of the variable
 print (len (message))
 OUTPUT-> 13

message = 'codinG Questt'
 print (message.count (codinG))      # to **count** the length of a **part** of value-> print(variable.count ())
 OUTPUT-> 6

message = 'codinG Questt'
 print (message.count (codinG))      # to **count** the number of **same alphabet** in the value-> print(variable.count ('t'))
 OUTPUT-> 2


 message = 'codinG Questt'
 print (message.lower())
 OUTPUT-> coding questt
 
 message = 'codinG Questt'
 print (message))
 OUTPUT-> CODING QUESTT
 
 # to find a value of a string
message = 'codinG Questt'
 print (message.find('codinG'))
 OUTPUT-> 1                        #output 1 when the word/numeric is found in our variable's value
 
 message = 'codinG Questt'
 print (message.find('Shilpa'))
 OUTPUT-> -1                       #output negative 1 when the word/numeric is NOT found in our variable's value
 
 # to replace one value with another
 message = 'codinG Questt'
 message.replace('Questt', 'enthusiast')
 OUTPUT-> will not work, one has to form and print a new variable (working)
 new_message = message.replace('quest', 'enthusiast')
 print (new_message)
 OUTPUT-> codinG enthusiast
 
 # How to print the output in a specific format say Hola, Shilpa. Beinvenido!
 1.
 greeting = 'Hola'
 name = 'Shilpa'
 message = greeting + ', ' + name + '.Bienvenido!' #string method
 print (message)
 OUTPUT->

2. 
 greeting = 'Hola'
 name = 'Shilpa'
 message = '{}, {}.Welcome!' #string and curly braces method
 message = 
 print (message)
 OUTPUT->

3.
greeting = 'Hola'
 name = 'Shilpa'
 message = greeting + ', ' + name + '.Bienvenido!'.format(greeting, name)
 print (message)
 OUTPUT->

4. 
 greeting = 'Hola'
 name = 'Shilpa'
 message = f'{greeting}, {name}. Welcome!'      f'{},{}'.  #f, string and curly braces method
 print (message)
 OUTPUT-> Hola, Shilpa. Beinvenido!


stringVariable = 'This is a string variable' #single quote for a single line
print (stringVariable)
print (stringVariable[0])
OUTPUT -> T

#----------------------------
# REVISIT OUTPUT FORMATTING

#-----------------------------------
# Slicing of a string variable using Index

print (stringVariable[0:12])
print (stringVariable[:12])
# Both of the above statements produce the same result from 0 till 7 th character which is index 0 to 6, spaces within the string are also calculated or taken into account
OUTPUT -> This is a st

# To print from 12th index to the end of the string
print (stringVariable[12:])
OUTPUT -> ring variable

# To print to zeroth index
print (stringVariable[:0])
OUTPUT -> empty space

# To print from 0 or zeroth index to 1th
print (stringVariable[0])
OUTPUT -> T
print (stringVariable[:1])
OUTPUT -> T

# To print from 0th index to -1
print (stringVariable[:-1])
OUTPUT -> This is a string variabl

#LIST


