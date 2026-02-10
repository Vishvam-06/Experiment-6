# Experiment-6
## Aim:
Study of conditional statements in python

## Theory:
Conditional statements in Python are used to perform decision-making operations in a program. They allow the execution of different blocks of code based on whether a given condition is true or false. Python provides conditional statements such as if, if–else, and if–elif–else to handle single as well as multiple conditions.
The conditions are formed using relational operators (>, <, >=, <=, ==, !=) and logical operators (and, or, not). When a condition is satisfied, the corresponding block of code is executed; otherwise, control passes to the next condition or the else block.In this experiment, conditional statements are used to solve various problems such as checking positive or negative numbers, determining even or odd numbers, finding the largest among values, assigning grades, checking leap years, validating dates, identifying vowels and consonants, and calculating salary and income tax.


## Algorithm:
1)Algorithm: Check Whether a Number is Positive, Negative, or Zero

Start
Read an integer number num from the user.
If num > 0,
Display “Positive”
Else if num < 0,
Display “Negative”
Else,
Display “Zero”
Stop

2)Algorithm: Check Whether a Number is Even or Odd

Start
Read an integer number num from the user.
If num % 2 == 0,
Display “Even”
Else,
Display “Odd”
Stop

3)Algorithm: Find the Largest of Three Numbers

Start
Read three integers a, b, and c from the user.
If a ≥ b and a ≥ c,
Display “Largest = a”
Else if b ≥ a and b ≥ c,
Display “Largest = b”
Else,
Display “Largest = c”
Stop

4)Algorithm: Assign Grade Based on Marks

Start
Read the marks of the student as an integer.
If marks ≥ 90,
Display “Grade A”
Else if marks ≥ 75,
Display “Grade B”
Else if marks ≥ 60,
Display “Grade C”
Else if marks ≥ 40,
Display “Grade D”
Else,
Display “Fail”

5)Algorithm: Check Whether a Year is a Leap Year

Start
Read the year as an integer.
If
the year is divisible by 400, OR
the year is divisible by 4 and not divisible by 100,
then
Display “Leap Year”
Else,
Display “Not a Leap Year”
Stop

6)Algorithm: Validate a Date and Find the Next Date

Start
Read the date from the user in dd/mm/yyyy format.
Split the date and store day as dd, month as mm, and year as yy.
Step 1: Find Maximum Days in the Month
If mm is 1, 3, 5, 7, 8, 10, or 12,
Set max1 = 31
Else if mm is 4, 6, 9, or 11,
Set max1 = 30
Else if mm is 2:
If yy is a leap year,
Set max1 = 29
Else,
Set max1 = 28
Else,
Display “Date is invalid” and Stop
Step 2: Validate the Date
If mm < 1 or mm > 12,
Display “Date is invalid” and Stop
Else if dd < 1 or dd > max1,
Display “Date is invalid” and Stop
Step 3: Increment the Date
If dd = max1 and mm ≠ 12:
Set dd = 1
Set mm = mm + 1
Else if dd = 31 and mm = 12:
Set dd = 1
Set mm = 1
Set yy = yy + 1
Else:
Set dd = dd + 1
Step 4: Display Result
Display the incremented date.
Stop

7)gorithm: Check Whether a Character is Vowel or Consonant

Start
Read a character ch from the user.
If ch belongs to the set {a, e, i, o, u, A, E, I, O, U},
Display “Vowel”
Else,
Display “Consonant”
Stop

8)Algorithm: Calculate Gross Salary

Start
Read the basic salary as a floating-point number.
If basic ≤ 10000:
Calculate hra = 0.20 × basic
Calculate da = 0.80 × basic
Else if basic ≤ 20000:
Calculate hra = 0.25 × basic
Calculate da = 0.90 × basic
Else:
Calculate hra = 0.30 × basic
Calculate da = 0.95 × basic
Calculate gross salary:
gross = basic + hra + da
Display the gross salary.
Stop

9)Algorithm: Calculate Income Tax

Start
Read the income as a floating-point number.
If income ≤ 2,50,000
Set tax = 0
Else if income ≤ 5,00,000
Calculate tax = (income − 2,50,000) × 0.05
Else if income ≤ 10,00,000
Calculate
tax = (2,50,000 × 0.05) + (income − 5,00,000) × 0.20
Else
Calculate
tax = (2,50,000 × 0.05) + (5,00,000 × 0.20) + (income − 10,00,000) × 0.30
Display the calculated income tax.
Stop


## Conclusion 
From this experiment, it is concluded that conditional statements play a vital role in Python programming as they enable logical decision-making and branching of programs. The use of if, elif, and else statements allows the program to handle multiple conditions efficiently.
