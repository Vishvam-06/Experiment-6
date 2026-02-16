# Experiment-6
## Aim:
Study of conditional statements in python

## Theory:
Conditional statements in Python are used to perform decision-making operations in a program. They allow the execution of different blocks of code based on whether a given condition is true or false. Python provides conditional statements such as if, if–else, and if–elif–else to handle single as well as multiple conditions.
The conditions are formed using relational operators (>, <, >=, <=, ==, !=) and logical operators (and, or, not). When a condition is satisfied, the corresponding block of code is executed; otherwise, control passes to the next condition or the else block.In this experiment, conditional statements are used to solve various problems such as checking positive or negative numbers, determining even or odd numbers, finding the largest among values, assigning grades, checking leap years, validating dates, identifying vowels and consonants, and calculating salary and income tax.


## Algorithm:
1)Algorithm: Check Whether a Number is Positive, Negative, or Zero

Step 1: Start
Step 2: Read an integer number num from the user.
Step 3: If num > 0,
Step 4: Display “Positive”
Step 5: Else if num < 0,
Step 6: Display “Negative”
Step 7: Else,
Step 8: Display “Zero”
Step 9: Stop

2)Algorithm: Check Whether a Number is Even or Odd

Start
Input a using a = int(input("Enter a number a:"))
Input b using b = int(input("Enter a number b:"))
Input c using c = int(input("Enter a number c:"))
If a > b and a > c, print "a is the greatest number"
Else if b > a and b > c, print "b is the greatest number"
Else, print "c is the greatest number"
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
Input subject using subject = int(input("Enter a subject:"))
If subject >= 90, print "Grade A"
Else if subject >= 75, print "Grade B"
Else if subject >= 60, print "Grade C"
Else if subject >= 40, print "Grade D"
Else, print "Fail"
Stop     

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

Step 1: Start
Step 2: Input & Parsing
        Accept a date string in dd/mm/yyyy format.
        Split the string by the / character and convert the day (dd), month (mm), and year (yy) into integers.
Step 3: Determine Maximum Days in Month
        If month is 1, 3, 5, 7, 8, 10, or 12: Set max1 = 31.
        Else, if month is 4, 6, 9, or 11: Set max1 = 30.
        Else, if the year is a Leap Year (divisible by 4 and not 100, or divisible by 400): Set max1 = 29.
        Otherwise: Set max1 = 28.
Step 4: Validate the Input Date
        If mm is not between 1 and 12, OR dd is not between 1 and max1: Print "Date is invalid" and stop.
Step 5: Increment Logic
        Case A (End of Month, not December): If dd == max1 and mm != 12:
        Set dd = 1, increment mm by 1.
        Case B (End of Year): If dd == 31 and mm == 12:
        Set dd = 1, mm = 1, and increment yy by 1.
        Case C (Standard Day): Otherwise:
        Increment dd by 1.
Step 6: Output – Display the incremented dd, mm, and yy.
Step 7: Stop

7)gorithm: Check Whether a Character is Vowel or Consonant

Step 1: Start
Step 2: Input – Accept a single character from the user and store it in the variable lett.
Step 3: Membership Check – Check if the character stored in lett exists within the string constant 'aeiouAEIOU'.
Step 4: Branching (Condition True) – If the character is found in that string:
Print the message "Vowel". 
Step 5: Branching (Condition False) – Else (if the character is not found in the string): Print the message "Consonant".
Step 6: Stop

8)Algorithm: Calculate Gross Salary

Step 1: Start
Step 2: Input – Read the basic salary from the user.
Step 3: Condition 1 – If basic is less than or equal to 10,000:Set HRA = 20% of basicSet DA = 80% of basic
Step 4: Condition 2 – Else, if basic is less than or equal to 20,000:Set HRA = 25% of basicSet DA = 90% of basic
Step 5: Condition 3 – Else (if basic is greater than 20,000):Set HRA = 30% of basicSet DA = 95% of basic
Step 6: Calculation – Calculate gross salary using the formula: $$gross = basic + HRA + DA$$
Step 7: Output – Display the calculated gross salary.
Step 8: Stop  

9)Algorithm: Calculate Income Tax

Step 1: Start
Step 2: Input – Read the income from the user.
Step 3: Bracket 1 (0% Tax)If income > 250,000:Set tax = 0
Step 4: Bracket 2 (5% Tax)Else, if income > 500,000:Calculate tax on the amount above 250,000: tax = (income - 250,000) * 0.05
Step 5: Bracket 3 (20% Tax)Else, if income $\le$ 1,000,000:Take the full tax from Bracket 2 (12,500) and add 20% of the amount above 500,000:tax = 12,500 + (income - 500,000) * 0.20
Step 6: Bracket 4 (30% Tax)Else (if income > 1,000,000):Take the full tax from Brackets 2 and 3 (12,500 + 100,000) and add 30% of the amount above 1,000,000:tax = 112,500 + (income - 1,000,000) * 0.30
Step 7: Output – Display the total calculated tax.
Step 8: Stop   


## Conclusion 
From this experiment, it is concluded that conditional statements play a vital role in Python programming as they enable logical decision-making and branching of programs. The use of if, elif, and else statements allows the program to handle multiple conditions efficiently.
