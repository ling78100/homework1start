# Homework Assignment 1, Methods in Computational Linguistics I, Fall 2017

Please consult the syllabus for detailed instructions regarding how to submit programming assignments and a list of grading criteria.   Deadline: September 25, 2017

Note:  Please submit assignment to the dropbox for homework 1 on the course Blackboard page.

## Problem 0: Install Python 3.5, Anaconda, and NLTK. This isn’t graded.

## Problem 1: Adapted from Chapter 2, Programming Exercise 6 (page 54)

Write a program by editing the file `invest.py` that computes the value of an interest bearing investment after n years. You should prompt the user for:

1. The amount added to the investment at the start of each year
2. The annual interest rate
3. The term or number of years of the investment

Your program should print out a table that contains the following:

1. The current year
2. The value of the investment at the start of the year
3. The interest earned in the current year
4. The value of the investment at the end of the year
5. The total amount of interest earned since the start of the investment

You might want to consult the `futval.py` program in section 2.7 of the textbook for ideas.

A sample run of the program is shown below:

```
Enter amount invested at start of each year: 100
Enter the annual interest rate in percent: 10
Enter number of years you plan to invest: 10

Year     Start   Interest        End      Total
         Value     (year)      Value   Interest
-----------------------------------------------
   1    100.00      10.00     110.00      10.00
   2    210.00      21.00     231.00      31.00
   3    331.00      33.10     364.10      64.10
   4    464.10      46.41     510.51     110.51
   5    610.51      61.05     671.56     171.56
   6    771.56      77.16     848.72     248.72
   7    948.72      94.87    1043.59     343.59
   8   1143.59     114.36    1257.95     457.95
   9   1357.95     135.79    1493.74     593.74
  10   1593.74     159.37    1753.12     753.12
```

## Problem 2: “Converting Kilometers to Miles”

### Do Programming Exercise 10 in Chapter 2 (page 55)

## Problem 3: “Averaging Numbers”

### Do Programming Exercise 14 in Chapter 3 (page 81)

## Problem 4: “The Nth Fibonacci Number”

### Do Programming Exercise 16 in Chapter 3 (page 82)

A Fibonacci sequence is a sequence of numbers where each successive number is the sum of the previous two. The classic Fibonacci sequence begins with 1, 1, 2, 3, 5, 8, 13, ... Write a program that computes the nth Fibonacci number where n is input by the user. For example for n=6 the output should be 8. 

A sample run is shown below:
```
Which Fibonacci number would you like?: 7
Fib 7 = 13
```
