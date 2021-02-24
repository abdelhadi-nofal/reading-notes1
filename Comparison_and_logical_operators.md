## Comparison and Logical Operators

### Comparison operators — operators that compare values and return true or false. The operators include: >, <, >=, <=, ===, and !==.
### Logical operators — operators that combine multiple boolean expressions or values and provide a single boolean output. The operators include: &&, ||, and !.
### Comparison Operators ### You may be familiar with comparison operators from math class. Let’s make sure there aren’t any gaps in your knowledge.

### Less than (<) — returns true if the value on the left is less than the value on the right, otherwise it returns false.
### Greater than (>) — returns true if the value on the left is greater than the value on the right, otherwise it returns false.
### Less than or equal to (<=) — returns true if the value on the left is less than or equal to the value on the right, otherwise it returns false.
### Greater than or equal to (>=) — returns true if the value on the left is greater than or equal to the value on the right, otherwise it returns false.
### Equal to (===) — returns true if the value on the left is equal to the value on the right, otherwise it returns false.
### Not equal to (!==) — returns true if the value on the left is not equal to the value on the right, otherwise it returns false.
### Logical Operators
### Comparison operators allow us to assert the equality of a statement with JavaScript. For example, we can assert whether two values or expressions are equal with ===, or, whether one value is greater than another with >.

### There are scenarios, however, in which we must assert whether multiple values or expressions are true. In JavaScript, we can use logical operators to make these assertions.

### && (and) — This operator will be truthy (act like true) if and only if the expressions on both sides of it are true.
### || (or) — This operator will be truthy if the expression on either side of it is true. Otherwise, it will be falsy (act like false).
### var isTrue = ('yellow' === 'green') && (4 >= 4);
### In the example above, we check if the string 'yellow' is equal to the string 'green' and (&&) if 4 is greater than or equal to 4. Let’s break this down into the two comparison expressions.
### The first expression is false, because the string 'yellow' is not the same (equal) as the string 'green'.
### The second expression is true, because the number 4 is greater than or equal to 4.
### The && operator requires that both expressions be true in order for the expression to be truthy. Because one expression is false and the other is true, the expression is falsy and evaluates to false.

## For, While and Do While LOOP in JavaScript

### How to use Loop?
### Loops are useful when you have to execute the same lines of code repeatedly, for a specific number of times or as long as a specific condition is true. Suppose you want to type a ‘Hello’ message 100 times in your webpage. Of course, you will have to copy and paste the same line 100 times. Instead, if you use loops, you can complete this task in just 3 or 4 lines.

### Different Types of Loops**
### There are mainly four types of loops in JavaScript.

### for loop**
### for/in a loop (explained later)**
### while loop
### do…while loop
