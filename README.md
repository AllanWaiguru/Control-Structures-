# Control-Structures-
Repetition control structures, including the for loop, while loop, and do...while loop, are used in programming to execute a certain block of code repeatedly until a specified condition is met. Each of these loops has its own use cases and is suitable for different scenarios.

For Loop:
Syntax:

python
Copy code
for variable in iterable:
    # code to be executed
When to Use:

Use a for loop when you know the number of iterations in advance or when you want to iterate over elements in a sequence (e.g., list, tuple, string).
It's particularly useful when the number of iterations is fixed or determined by the length of a sequence.
Example (in Python):

python
Copy code
for i in range(5):
    print(i)
This will print numbers 0 through 4.

While Loop:

Syntax:

python
Copy code
while condition:
    # code to be executed
When to Use:

Use a while loop when the number of iterations is not known in advance, and the loop should continue as long as a certain condition is true.
It's useful when you want to repeat a block of code until a specific condition is met.
Example (in Python):

python
Copy code
count = 0
while count < 5:
    print(count)
    count += 1
This will print numbers 0 through 4.

Do...While Loop:

Syntax:

python
Copy code
while True:
    # code to be executed
    if not condition:
        break
When to Use:

The do...while loop is less common in languages like Python, but it's used when you want to ensure that the loop body is executed at least once, regardless of whether the condition is initially true or false.
In Python, you can simulate a do...while loop using a while True loop and breaking out of it based on a condition.
Example (in Python):

python
Copy code
count = 0
while True:
    print(count)
    count += 1
    if count >= 5:
        break
This will also print numbers 0 through 4.

In summary:

Use a for loop when the number of iterations is known.
Use a while loop when the number of iterations is not known in advance and depends on a condition.
Use a do...while loop (simulated in Python) when you want to ensure that the loop body is executed at least once before checking the condition.
