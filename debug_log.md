# debug_log.md
# Author: Simone Menchini

## Bug 1
Error type: KeyError
File + line: week8_buggy.py, line 4
What the error means: Python cannot find the dictionary key 'amount' in the first record because it is misspelled as 'amout'.
What I told the duck: The program is trying to access a dictionary key that does not exist.
What I tried: I checked the dictionary keys and compared them with the key used in the function.
How I fixed it: I changed 'amout' to 'amount' on line 4

## Bug 2
Error type: TypeError
File + line: week8_buggy.py, line 16
What the error means: Python cannot compare an integer with a string using the > operator.
How I fixed it: I removed the quotation marks around '1000', changing it to 1000.

## After fixing both bugs
Final output: Total: $5150.00 across 3 records
True
Did pytest pass: Yes

## AI Literacy reflection
Did I use AI? No, I was able to read the code, analyzing it line by line and notice the 2 errors
What I changed myself: the 2 errors in line 4 and line 16
Can I explain every fixed line? Yes

## What I learned
I learned how to identify a KeyError caused by a misspelled dictionary key and a TypeError caused by comparing an integer to a string. 