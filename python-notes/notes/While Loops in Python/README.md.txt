This project contains multiple examples demonstrating the use of the **`while` loop** in Python.  
The `while` loop repeatedly executes a block of code as long as a specified condition evaluates to `True`.

---

## 📌 Concept
The general syntax of a **`while` loop** is:

```python
while condition:
    # code block
else:
    # optional else block
The loop body runs until the condition becomes False.

The optional else block executes when the loop condition becomes False (and the loop terminates normally).

🛠 Examples in This Project
This project covers:

Counting down from 10 to 1.

Counting up from 0 to 10.

Counting up to different ranges with increments of 1 and 2.

Using user input inside a while loop.

Using the else clause with while.

Example 1 – Countdown
python
Copy
Edit
i = 10
while i > 0:
    print(i)
    i = i - 1
Output:

python-repl
Copy
Edit
10
9
8
...
1
Example 2 – Count Up
python
Copy
Edit
h = 0
while h <= 10:
    print(h)
    h = h + 1
Example 3 – Step Increments
python
Copy
Edit
f = 1
while f <= 23:
    print(f)
    f = f + 2
Example 4 – User Input Loop
python
Copy
Edit
x = int(input("Enter your value of number: "))
while x <= 50:
    x = int(input("Enter your value of number: ")) 
    print(x)
print("Done with the value")
Example 5 – else with While
python
Copy
Edit
count = 5
while count > 0:
    print(count)
    count = count - 1
else:
    print("I am inside the else")
Output:

arduino
Copy
Edit
5
4
3
2
1
I am inside the else
🎯 Purpose
Understanding the syntax and use cases of the while loop.

Practicing loop control with different conditions and increments.

Learning how to use the optional else block in loops.

