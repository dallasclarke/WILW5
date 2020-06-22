# What I learned Week 5.

---

## If and Else 

Very often when you are writing code, you are going to want the ability to perform different actions based on different decisions. This is where If and Else statements come into play.

- "if" is used to specify a block of code to be executed if a specified condition is true.
- "else" is used if the same condition is false.
- "else if" is to specify a new condition to test if the first condition is false.

**Example**

if (condition) {
    // Code to be executed if true.
}

## Switch statements

The switch statement evaluates an expression, matching the expression's value to a case clause, and executes statements associated with that case, as well as statements in cases that follow the matching case. Using the switch statement you can select one of many different code blocks to be executed.

- The keyword "break" is used to break out of the switch block by stopping the execution inside. 
- The "default" keyword specifies the code to run if there is no match. The "default" keyword does not have to be the last case inside of the switch block.

It is important to remember if multiple cases match a case value the first case will be selected. You can also have different cases share the same code.

