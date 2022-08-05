# Loops #

-Loops offer a quick and easy way to do something repeatedly

-You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another

-There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times

-A for loop repeats until a specified condition evaluates to false

-A for statement looks as follows:

for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement

1. The initializing expression initialExpression, if any, is executed

2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute

3. The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.

4. If present, the update expression incrementExpression is executed

5. repeat from step 2 

-The do...while statement repeats until a specified condition evaluates to false

-A do...while statement looks as follows:

do
  statement
while (condition);

-statement is always executed once before the condition is checked

-If condition is true, the statement executes again. At the end of every execution, the condition is checked.