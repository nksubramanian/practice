# Nested if

Nested if has if statements within an if statement. Nested if is used when there are multiple if statements are to be checked. 
The difference between Nested if and elif is that in Nested if, multiple conditions are checked while elif there is a priority of if statements.


# Syntax\
if condition1:\
--if condition2:\
---->statement

In the above syntax, statement would get executed only if both conditions are satisifed.

Of course, the above is logically equivalent to the below

if condition1 AND condition2:\
-->statement

Here is an example to check if a number is odd or even, removing the case of 0


