# 10-4-2016-Discussion-and-AP-Java-Practice

Discussion: 


What is the most important language in the history of programming?
- Chris Lee: C, base that built the foundation
- Tim: (to him) C++, taught him the most 
- Chris Kim: C, cuz it’s old 
- James: UNIX, Linux, No UNIX, no C  
- Tommy: UNIX


What is the most powerful language? 
- Chris Lee: Depends, but the most effective one is Java. Java 
- Tim: Java
- Chris Kim: Java
- James: Java, widespread adoption, good recognition  
- Tommy: C 


What is the most convenient language? 
- Chris Lee: Java  
- Tim: Python, short and easy
- Chris Kim: Python, Just Basic 
- James: Python
- Tommy: Java


What is the language you want to master? 
- Chris: C, never learned it 
- Tim: Java, frequently used, popular 
- Chris Kim: C, to build robots and complicated programs to take over the world 
- James: Java, English of programming 
- Tommy: C, it’s fun and has lots of potential 


How was Java made? 
- By mistake 


Answer to Q1: 
- value is unchanged before it is printed the first time, so the first number output is 15. value is incremented after the call to println and the loop stops when value == 28 so the last number output is 27.


Answer to Q2:
- Case I: The && operation evaluates to true if and only if both operands are true. The condition in Case I is evaluated as (bonusOne && bonusTwo) && bonusThree. For the condition to evaluate to true all 3 variables must be true. This correctly implements the intended condition.
- Case II: The || operation is true if at least 1 operand is true. The condition in Case II evaluates to true if at least 1 of the variables is true, which is not the intent.
- Case III: The conditions are evaluated independently. It is possible for grade to be incremented by 0, 5, 10 or 15 points depending on the values of the variables. This is not the intent.
