#**EXPERIMENT 7 : *Study of Loops in Python***

##*AIM*: **To study and implement different types of looping statements in Python and understand their use in solving repetitive computational problems.** 

*THEORY*:

Loops are control structures used to execute a block of code repeatedly.

Python mainly has two types of loops: while loop and for loop.

A while loop runs as long as the given condition is true.

Loops help reduce repetition and make programs efficient.

Break statement stops the loop immediately when a condition is met.

Continue statement skips the current iteration and moves to the next one.

Loops are used in programs like factorial calculation, Fibonacci series, palindrome checking, digit counting, and searching elements.

*ALGORITHM*:

*Program 1: Print numbers from 1 to 5 using while loop*

     Start
     Initialize variable i = 1
     Check if i ≤ 5
     Print i
     Increment i by 1
     Repeat steps 3–5 until condition becomes false
     Display Result
     

*Program 2:Print numbers from 1 to N*

     Start
     Input value n
     Set i = 1
     Check if i ≤ n
     Print i
     Increment i
     Repeat until condition fails
     Display Result

*Program 3: Factorial of a number*

     Start
     Input number n
     Set fact = 1
     While n > 0
     Multiply fact with n
     Decrease n by 1
     Print factorial
     Display result

     
*Program 4: Fibonacci series using while loop*

        Start
        Input number of terms n
        Initialize a = 0, b = 1, i = 1
        While i ≤ n
        Print a
        Find next term c = a + b
        Update a = b, b = c
        Increment i
        Display

*Program 5: Adding limit to Fibonacci series*

        Start
        Input limit value
        Set a = 0, b = 1
        While a ≤ limit
        Print a
        Update a, b = b, a+b
        Display Result

        
*Program 6: Reverse a number*

        Start
        Input number
        Set rev = 0
        While number > 0
        Extract last digit
        Update reversed number
        Remove last digit from original number
        Print reversed number
        Display

*Program 7: Check Palindrome number*

       Start
       Input number
       Store original number
       Reverse the number
       Compare original and reversed numbers
       Display result

*Program 8: Checking Palidrome for string*

      Start
      Input string
      Set two pointers at start and end
      Compare characters
      Move pointers toward center
      If mismatch occurs, not palindrome
      Display result

*Program 9: Another method for checking Palindrome*

       Start
       Input string
       Reverse string using slicing
       Compare original and reversed string
       Display result

*Program 10: Count digits in a number*

     Start
     Input number
     Set counter = 0
     While number > 0
     Divide number by 10
     Increment counter
     Print counter
     Display Result
     

*Program 11: Exit the loop when i is 3*

    Start
    Initialize i = 1
    Print i
    If i = 3, stop loop
    Increment i
    Display

*Program 12: Search an element in a list*

    Start
    Define list
    Input search element
    Traverse list using loop
    If element matches, print position
    If not found, display message
    Stop

*Program 13: Print only odd numbers (1 to 10)*

    Initialize i = 0
    Increment i
    If i is even, skip iteration
    Print i
    Repeat until 10
    Display Result

*CONCLUSION:*

This experiment helped in understanding the concept of loops in Python. Different types of looping operations such as while loop, break statement, and continue statement were implemented. Programs like factorial, Fibonacci series, palindrome checking, digit counting, and searching elements demonstrated how loops simplify repetitive tasks and improve programming efficiency. The experiment enhanced logical thinking and programming skills.
