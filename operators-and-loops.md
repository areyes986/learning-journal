# Operators and Loops #

## Comparison operators: Evaluating Conditions ##

You can evaulate a situation by comparing one value in the script to what you might expect it to be. The result will be a Boolean: *true* or *false*.

- `==` is equal to
    - this compares two values to see if they are the same

- `!=` is NOT equal to
    - this compares to see if they are NOT the same

- `===` strict equal to
    - compares two values to check that both *data type* and *value* are the same
    
- `!==` strict NOT equal to
    - compares two values to check that both *data type* and *value* are NOT the same

- `>=` greater than or equal to
- `<=` less than or equal to

## Logical Operators ##

Allows you to compare the results of more than one comparison operator. (&&)

```
((5<2) && (2 >= 3))
```
They both evaluate to *false*


- `&&` Logical And
    - tests more than one condition

- `||` Logical Or
    - tests at least one condition

- `!` Logical Not
    - takes a single Boolean value and inverts it

## Loops ##

Looks check a condition. If returned *true*, a code block will run. Condition will be checked again and if it still returns true, code block will run again. It repeats condition until condition returns false. 

Three common loops:

1. For
    - used if you need to run code a specific number of times (most common)

1. While
    - used if you do not know how many times the code should run.

1. Do While
    - similar to *while* but it will always run the statements inside the curly braces at least once, even if condition is false

## Loop Counters ##

*For* loop uses a counter as a condition. It instructs the code to run a specific # of times.

Condition is makde up of three statements:

1. Initialization
1. Condition
    - loop will continue to run until counter reaches the number
1. Update
    - when loops has tun the statements in curly braces, it adds one to the counter


if (true){
    //do the thing;
}

loop

for (this; many; time;){
    //do the thing
}

while (true){
    //do the thing
}