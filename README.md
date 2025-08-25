**1. Description**
A Python program that generates a random secure password based on the user's choice of how many letters, symbols, and numbers to include. It supports an "easy" version where characters are appended in order, and a "hard" version where the characters are shuffled before combining, ensuring better randomness.

**2. How It Works**
The program asks the user how many letters, symbols, and numbers they want in their password.

It randomly selects the requested number of characters from predefined lists.

In the hard level, it shuffles the chosen characters before combining them.

It outputs the generated password to the user.


**3. Operators and Functions Used**

Operators:
= (Assignment): Used to assign values to variables such as nr_letters, password_list, and password.

+= (Augmented Assignment): Used implicitly in .append() (method call).

for: Used for looping over a range to add characters multiple times.

in: Used in for loops to iterate over a range or list.

[] (Indexing/Appending): append() method uses the square brackets list structure.

() (Parentheses): Used in function calls and method calls.


Functions and Methods:

print(): Outputs messages and the final password.

input(): Collects user input as strings.

int(): Converts string input to integer for numeric operations.

append(): Adds an element to the end of a list.

join(): Concatenates list elements into a single string (the final password).

random.choice(): Selects a random element from a list for password character selection.

random.shuffle(): Randomly shuffles the list to enhance password randomness
