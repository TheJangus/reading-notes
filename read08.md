**Read: 08 - Operators and Loops**

&& -- and
|| -- or
!  -- not (bang)

[Expressions and operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

At a high level, an expression is a valid unit of code that resolves to a value

There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.

The expression x = 7 is an example of the first type
 * This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to 7.

 The expression 3 + 4 is an example of the second type
  * This expression uses the + operator to add 3 and 4 together and produces a value, 7

**Comparison operators**
A comparison operator compares its operands and returns a logical value based on whether the comparison is true. 

**Assignment operators**
An assignment operator assigns a value to its left operand based on the value of its right operand. 
  * The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. 

If an expression evaluates to an object, then the left-hand side of an assignment expression may make assignments to properties of that expression. 

If an expression does not evaluate to an object, then assignments to properties of that expression do not assign:


[Loops and iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)
Loops offer a quick and easy way to do something repeatedly.
You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another.

**for statement**
A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

When a for loop executes, the following occurs:

1. The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)
3. The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.
4. If present, the update expression incrementExpression is executed.
5. Control returns to Step 2.

**while statement**
A while statement executes its statements as long as a specified condition evaluates to true

while (condition)
  statement
  
 If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.
 
 The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.
 
 To execute multiple statements, use a block statement ({ }) to group those statements.
 
 Avoid infinite loops. Make sure the condition in a loop eventually becomes false—otherwise, the loop will never terminate! 
 





 
