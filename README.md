# Java_If_else_Condition
* Less than: a < b
* Less than or equal to: a <= b
* Greater than: a > b
* Greater than or equal to: a >= b
* Equal to a == b
* Not Equal to: a != b

**Java has the following conditional statements:**

Use if to specify a block of code to be executed, if a specified condition is true
Use else to specify a block of code to be executed, if the same condition is false
Use else if to specify a new condition to test, if the first condition is false
Use switch to specify many alternative blocks of code to be executed

# The if Statement
Use the if statement to specify a block of Java code to be executed if a condition is true.
# Syntax
if (condition) 
 
 {
  
  // block of code to be executed if the condition is true
  
}
# The else Statement
**Syntax**

if (condition) 

{

  // block of code to be executed if the condition is true
  
} 

else

{

  // block of code to be executed if the condition is false
  
}
# The else if Statement

Syntax


if (condition1) 

{
  
  // block of code to be executed if condition1 is true
}

else if (condition2) 

{
 
 // block of code to be executed if the condition1 is false and condition2 is true
 
} 

else

{

  // block of code to be executed if the condition1 is false and condition2 is false
  
}

# Short Hand If...Else

**Syntax**

variable = (condition) ? expressionTrue :  expressionFalse;

Example:

int time = 20;

String result = (time < 18) ? "Good day." : "Good evening.";

System.out.println(result);
