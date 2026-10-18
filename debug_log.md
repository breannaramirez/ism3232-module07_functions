
# Debug Log
# Author: Breanna Ramirez

## Bug 1
Error type: KeyError
File + line: week8_buggy.py, line 12
What the error means: Python tried to access a dictionary key that doesn't exist.
What I told the duck: The function starts the total at 0, then loops through each record and adds its amount to the total. After going through all the records, it returns the sum.
What I tried: I added a print statement inside the loop to see which record was causing the error.
How I fixed it: The first record had a typo in the key 'amount'. I corrected 'amout' to 'amount' and removed the DEBUG print.

## Bug 2
Error type: TypeError
File + line: week8_buggy.py, line 16
What the error means: Python can't compare an integer and a string using >.
How I fixed it: I removed the quotation marks around 1000 so that Python compares two integers instead of an integer and a string.

## After Fixing Both Bugs
Final output:
Did pytest pass?

## AI Literacy Reflection
Did I use AI? Yes
If yes -- exact prompt I used:
What AI explained:
What I changed myself:
Can I explain every fixed line?

## What I learned
