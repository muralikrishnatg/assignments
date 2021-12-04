1.What are the two values of the Boolean data type? How do you write them? – True, False
2. What are the three different types of Boolean operators? - and, or, not
3. Make a list of each Boolean operator's truth tables (i.e. every possible combination of Boolean values for the operator and what it evaluate ). – 
A	B	A and B
(True if both are True)	A or B
(True if anyone is True)	not a
(toggle the value of a)	not b
(toggle the value of b)
True	False	False	True	False	True
True	True	True	True	False	False
False	False	False	False	True	True
False	True	False	True	True	False
4. What are the values of the following expressions?
(5 > 4) and (3 == 5)	False
not (5 > 4)		False
(5 > 4) or (3 == 5)	True
not ((5 > 4) or (3 == 5))   False
(True and True) and (True == False)  False
(not False) or (not True)		True			
5. What are the six comparison operators?
< (less than)
> (greater than)
<= (less than or equal to)
>= (greater than or equal to)
== (equal to)
!= (not equal to)
6. How do you tell the difference between the equal to and assignment operators? Describe a condition and when you would use one.
= is used to assign a value to a variable. eg: country = ‘India’
== is used to compare two values. returns 1 if the value is True eg: country == ‘India’
7. Identify the three blocks in this code:
# Identified blocks and highlighted in blue colour
spam = 0
if spam == 10:
print('eggs')
if spam > 5:
print('bacon')
else:
print('ham')
print('spam')
print('spam')
8. Write code that prints Hello if 1 is stored in spam, prints Howdy if 2 is stored in spam, and prints Greetings! if anything else is stored in spam.
spam = int(input())
if spam == 1:
    print("Hello")
elif spam == 2:
    print("Howdy")
else:
    print("Greetings!")
9.If your programme is stuck in an endless loop, what keys you’ll press?
Ctrl + c / Ctrl + z / interrupt the kernel (in Jupyter notebook)
10. How can you tell the difference between break and continue?
The break statement is used to terminate the loop or statement. If the break statement is present in the nested loop, then it terminates only those loops which contains break statement.
continue is also a loop control statement just like the break statement. continue statement is opposite to that of break statement, instead of terminating the loop, it forces to execute the next iteration of the loop.
11. In a for loop, what is the difference between range(10), range(0, 10), and range(0, 10, 1)?
All 3 range statements will iterate 0 – 9. all statements outcome is same. 
12. Write a short program that prints the numbers 1 to 10 using a for loop. Then write an equivalent program that prints the numbers 1 to 10 using a while loop.
# using for loop
for i in range(1, 11):
    print(i, end=" ")

# using while loop
i = 1
while i <= 10:
    print (i, end = " ")
    i += 1
13. If you had a function named bacon() inside a module named spam, how would you call it after importing spam?
spam.bacon()
