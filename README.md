This project is written in Python

PROGRAM-1
The logic I used in the code is:

Take inputs → two numbers (a, b) and an operation type (add, sub, mul, div).

Use a class → Store these inputs in a Calculator object.

Check the operation using if-elif conditions.

If "add" → perform addition.
If "sub" → perform subtraction.
If "mul" → perform multiplication.
If "div" → perform division (only if denominator ≠ 0).
Return the result and print it.

PROGRAM-2:
The logic I used in Problem-2 is very simple and clear:

Take an integer input a.

Use a for loop from 1 to a.

In each iteration, generate the i-th odd number using the formula:

2
×
𝑖
−
1
2×i−1

Print the numbers in sequence.

PROGRAM-3:
The logic I used in Problem-3 is:

Take input → a single integer a.

Check if a is even → if yes, subtract 1 (so that the sequence always ends with an odd number).

Use a loop from 1 to the updated a.

Generate odd numbers using the formula 2*i - 1.

Print the sequence of odd numbers.


PROGRAM-4:
Here’s the logic I used in Problem-4:

Input list of numbers is given.

Create an empty dictionary result to store counts.

Loop from 1 to 9 (since we need multiples of 1–9).

For each i in 1–9:

Check each number in the list.

If num % i == 0 → that number is divisible by i, so increase the count.

Store the final count in the dictionary as {i: count}.

Print the dictionary.