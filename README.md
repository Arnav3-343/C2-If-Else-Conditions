## If/Else Conditional statements
Used for descision-making operations with conditions

Conditional statements always start with an 
`if` header
`elif` optional , but we can have  as many as we want
`else` optional, but only 1 for very `if`

### Condition:
An expression that evaluates to produce a reuslt which is a Boolean value (AKA Boolean expression)

### Indentation: 
Python relies on indentation to define scope in the code

### Formula:
if (Condition:
> Body statements

elif(Condition):
>  Body statement

else:
> Body Statement
*Ex. *
'''
a=2
if(a==0): # False
print("hi")
else:
print("bye")
'''
 > bye

 ## Nested Conditional statements

 A conditional statement inside another conditional statement

 ### Indentation

 The header/clause of a nested conditional statement must be indented from an outer header

 ### Formula:

 if(condition)
 if(condition): <-- Starting a nested statement
Body Statement 
elif(condition):
Body Statement
else:
Body Statement: <-- End of nested statement
elif(Statement)
 Body Statement
 else:
  Body Statement


  Ex.


  x=10
  y=10
  if(x < y):
   print("x is less than y")
   else:
   if(x > y):
   print("x is greater than y")
    else:
    print("x and y must be equal")
    > x and y must be equal

    ## order of operations

    1.() Parentheses
    2.** Exponents
    3.-a, +a Negeative, positive arguements
    4. *, /,//. % Multiplication ,Division,Quotient,Modulus
    5.+,- ,Addition, Subtraction
    6.<,<=, >,>=, ==, != Comparicon Operators
    7.not Boolean not
    8.And Boolean and
    9.or Boolean or

a++ --> a=a+1
a -- --> a=a-1