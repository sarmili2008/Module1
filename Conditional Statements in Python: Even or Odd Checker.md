# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
   num = int(input("Enter a number: "))

   # Checking if the number is even or odd
   if (num % 2) == 0:
        print(f"{num} is Even")
   else:
        print(f"{num} is Odd")
## Output
    Enter a number:
    7
    7 is Odd
## Result:
Thus,the python program to check the number whether even or odd is done successfully.
