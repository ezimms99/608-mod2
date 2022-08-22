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
- Repetition Statements: Provides two repition statements: while and for:
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

Program Development: Sequence-controlled repition
- Requirements statement: Describes what a program is supposed to do, but not how the program should do it. 
- Pseudocode for the algorithm: Lists the actions to execute
- Coding the Algorithm in Python: Execution phases
        - Initialization phase: Creates the variables needed to process the grades and set variables to appropriate initial values.
        - Processing phase: Processes the grades, calculating the running total, and counting the number of grades processed so far. 
        - Termination phase: Calculates and displays the average. 
- Introdution to Formatted strings: Dictated by an f'Class average is {average}'. The letter f before the string's opening quote indicates f-string. Use {} to specify values. When evaluated the program will use replacement text  to change average. 

Program Development: Sentinel-Controlled Repition 
- Sentinel value: Used to mark the end of data entry. 
- Sentinel controlled repition is often called indefinite repition because the number of repititions is not known before the loop begins executing. 
- Use a technique called top-down, stepwise refinement. 
        - Begin with pseudocode at the top, displays the program's overall function
        - Refinement process: Decompose top sequence into smaller tasks - called divide and conquer 
            - First refinement: Not super detailed
            - Second refinement: Commit to specific variables, define exact steps. 
- Format specifier: Describes how to format the replacement text. Can be written as print(f'Class average is {average:.2f}')
        - This will use two decimal places and if a number only contains one decimal a trailing 0 will follow. 

Program Development: Nested Control Statements 
- Can put an if...else statement within a for statement and it's considered to be "nested" in the loop. 

Built-In Function range: A deeper Look
- Two-argument version: Produces a sequence of consecutive integers from its first argument's value up to, but not including the second argument's value
- Three-argument version: Produces a sequence of integers from its first argument's value up to, but not including, the second argument's value, incrementing by the third argument's value known as the step. 
- Third-argument negative: If last value is negative the values decrease by that step. 

Using Type Decimal for Monetary Amounts
- Built in types: int(integers), float(floating point numbers like 7.5), and strings('Python'). There is not a built in decimal. 
- Must import decimal: import decimal and refer to the decimal type as decimal.Decimal OR from decimal import Decimal. 
- Decimal supports standard arithmetic 
- Field width specifies the number of character positions. For example {year:>2} right aligns years to two values. You can also left alight values with <. 

Break and Continue Statements: 
- Break: In a while or for statement exits that statement. 
- Continue: In a while or for loop skips the remainder of the loops suite. 

Boolean Operators: 
- AND: Tests if both conditions are true 
- OR: Evaluates if one or the other conditions are true
- Short circuit evaluation stops evaluating as soon as a condition determines the output of the function. If an AND statement 1 is false, it stops. If an OR statement 1 is true, it stops. 
- NOT: "Reverses" the meaning of a condition, True becomes False and vise versa. This is a Unary Operator (only one operand). 

Intro to Data Science: Measure of Central Tendency - Mean, Median, Mode
- Mean: The average value in a set of values
- Median: The middle value when all the values are arranged in sorted order
- Mode: The most frequently occuring value
- These are measures of central tendency - each is a way of producing a single value that represents a "central" value in a set of values. 
- Must import statistics to use functions mean, median, and mode. 
- To use functions: statistics.mean(DATA SET), statistics.median(DATA SET), statistics.mode(DATA SET)
