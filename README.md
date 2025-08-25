# Between-9-and-21

Question Explanation:

Input: 2 4 16

Output: True

The program is designed to determine if any of the three given integers, A, B, and C, falls within the range between 9 and 21.

Logical Approach:

Read Input:

Read three integers from input, representing A, B, and C.

Check if Numbers are Between 9 and 21:

For each number (A, B, and C):

Check if the number is greater than 9 and less than 21. This is done by using logical operators: number > 9 and number < 21.

Store the result of this check (True/False) for each number in separate variables: is_between_A, is_between_B, and is_between_C.

Determine the Output:

Use a logical or operation to combine the results of is_between_A, is_between_B, and is_between_C. If any of these values is True, the overall result will be True. Otherwise, it will be False.

Print the boolean result.

Example for Clarity:

If the input numbers are A = 2, B = 4, and C = 16:

A (2) is not between 9 and 21, so is_between_A is False.

B (4) is not between 9 and 21, so is_between_B is False.

C (16) is between 9 and 21, so is_between_C is True.

Since C satisfies the condition, the output will be True.

The output for these inputs will be: True
