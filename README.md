# 608-mod2
Notes and Exercises for Module 2

Chapter 3 Notes: 
Algorithms
- Procedure for solving a problem in terms of:
    - The actions to execute 
    - The order they are executed in
- Program control specifies the order in which the statements execute in a program. 

Pseudocode 
- Informal english-like language for "thinking out" algorithms
- Statements that specify the actions you want to take and the order you want to take them in. 

Control Statements 
- Typically statements execute sequentially but with a control statements you can execute a statement other than the next one in a sequence. 
3 forms of control
- Sequential Statements: Python statements execute one after the other unless directed otherwise. 
    - Flowcharts show sequential execution. Use a rectangle for actions and flowlines to show the order. In a flowchart for complete algorithm the first symbol is a rounded rectangle containing the word begin. The last is a rounded rectangle containing end. In part of an algorithm you use circles in their place called connector symbols. Decision symbols indicated that a decision is to be made such as an if statement. 
- Selection Statements: Python provides three types of statements that execute code on a condition that evaluates to true or false. 
    - If statement (single selection), if action is true it does the action if false it skips. 
    - If...else statement (double selection), performs action if true or performs different action if false. 
    - if...elif...else statement (multiple-selection), performs one of many actions depending on truth or falsity of conditions. 
- Repetiion Statements: Provides two repition statements: while and for:
    - While statement repeats an action as long as condition remains true
    - For repeats an action for every item in a sequence of items. 
    
If Statements:
- Indentation after if statement is important!! You must also have same indentation for multiple statements. 
- If statement flowcharts
    - The decision symbol is a diamond and if not executed the flowline skips the action and if true it moves to execute the action. 
- Remember!!! The = sign assigns a value to a name and the == sets that value as an equality operator. 

If...else and if...elif...else statements: 
- If and else are indented by the same amount
- You can go up using up arrows and recall code used but make modifications. 
- Conditional expressions allow you to set values equal to something with an if type statement. 
- if...elif...else tests many different conditions and the final else condition is optional. 
- Incorrectly indented code results in a nonfatal logic error. 
- A fatal logic error displays a traceback and terminates the script. 

While Statements: 
- Allows you to repeat one or more actions while a condition remains true. Often called a loop. 
- If you do not have a statement to where the condition eventually becomes false your code will get stuck in an infinite loop. 

For Statements: 
- Allows you to repeat an action or several actions and performs it for each item in a sequence. 
- Using end='  ' adds two spaces between characters and keeps everything on the same line, without it \n would be executed each time. 
- Sep specifies the string that appears between the items that print displays. 
- To remove the spaces use an empty string with no characters between its quotes. 

Iterables, Lists, and Iterators: 
- Iterable: Object from which the for statement ccan take one item at a time until no more items remain. 
- List: Comma-separated collection of items enclosed in square brackets. 
- Iterator: Like a book-mark keeping track of where it is in the sequence. 

Built-In range Function:
- Represents a sequence of consecutive integer values starting from 0 and continuing up to but not including the argumentative value. 
- Off-by-one error occurs when you assume range includes final number. 

Augmented Assignments: 
- Abbreviate assignment expressions in which the same variable name appears on the left and right of the assignment's =. 
- Addition augmented assignment (+=) first adds the number's value to the current total and then stores the new value in total. 

Left off at 3.10!
