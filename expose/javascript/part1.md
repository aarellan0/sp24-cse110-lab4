1. Line 9 prints the sum between num1, and num2, in this case, 20. values added: 20

2. Line 13 returns the sum 20, since the result is a var variable, which can be accessed elsehwhere in the function. final result: 20

3. line 9 returns - values added: 20

4. line 13 returns error, because result was declared with let, so its scope is limited to the if statement, thus the console log afterwards has no access to it

5. line 9 returns an error, because result tried to be reassigned, however it was declared as a constant, meaning it can't be changed.

6. in line 13, an error is returned for the same reason as q5, result is a const that tried to be re-assigned.
