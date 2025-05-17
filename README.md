# Chess Win Codechef


This C++ program reads two integers, `a` and `b`, from the user input and calculates the number of integers in the inclusive range from `a` to `b`. 

The core logic lies in the expression `b - a + 1`, which gives the count of numbers between `a` and `b`, including both endpoints. For example, if `a = 3` and `b = 7`, then the integers in that range are 3, 4, 5, 6, and 7 — a total of 5 numbers. The program then outputs this result.

 This logic assumes that `a <= b`; if `a > b`, the result will be zero or negative, which might not be meaningful in such a context without additional checks.

## Types of Loops in C++:
#### for loop – when you know how many times to repeat
for (int i = 0; i < 5; i++) { cout << i << " "; } Output: 0 1 2 3 4

#### while loop – when you repeat as long as a condition is true
int i = 0; while (i < 5) { cout << i << " "; i++; }

#### do...while loop – similar to while, but runs at least once
int i = 0; do { cout << i << " "; i++; } while (i < 5);
