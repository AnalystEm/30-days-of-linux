# Day 25 - Bash Conditional Statements and Loops

## Objective

My goal for today was to understand how conditional statements and loops work in Bash, and learn how they can be used to make scripts smarter, more dynamic, and more useful for automation.

---

## What I Learned

- Conditional statements allow Bash scripts to make decisions based on whether a condition is true or false.
- The basic `if` statement in Bash follows the structure `if [ condition ]`, followed by `then` and ending with `fi`.
- The `if` statement can be used to check if a file exists or whether a condition is true before taking action.
- The `if-else` statement handles both the true and false outcomes of a condition.
- The `if-elif-else` statement is useful when checking multiple possible conditions.
- File test operators in Bash include `-f` for file exists, `-d` for directory exists, `-e` for file or directory exists, and `-s` for file is not empty.
- String comparison operators include `==`, `!=`, and `-z`.
- Numeric comparison operators include `-eq`, `-ne`, `-gt`, `-lt`, `-ge`, and `-le`.
- Multiple conditions can be combined using `&&` for AND and `||` for OR.
- The `case` statement is useful when handling several possible matches in a cleaner way.
- A `for` loop is used to repeat commands for each item in a list.
- A `for` loop can be used to loop through numbers, files, or sequences.
- The `seq` command can be used to generate a sequence for looping.
- A `while` loop runs as long as a condition remains true.
- `while` loops are useful for repeating checks until something changes, such as waiting for a file to appear.
- Loop control statements such as `break` can be used to stop a loop early when needed.

---

## What I Built / Practiced

- Studied how decision-making works in Bash using conditional statements.
- Learned the structure and use cases of `if`, `if-else`, and `if-elif-else`.
- Reviewed common file, string, and numeric comparison operators in Bash.
- Learned how multiple conditions can be combined with AND and OR logic.
- Studied how the `case` statement works for handling multiple possible values.
- Learned how `for` loops work in Bash and how they can be used with lists, files, and sequences.
- Studied the `while` loop and how it can repeatedly check conditions.
- Reviewed how `break` can be used to control loop execution.

---

## Challenges Faced

- It took some time to understand the different comparison operators and when to use each one.
- The structure of `if`, `elif`, `else`, and `fi` needed careful attention to avoid confusion.
- Combining conditions with `&&` and `||` was a little tricky at first.
- The difference between `for`, `while`, and `case` became clearer only after reading through several examples.

---

## Key Takeaways

- Conditional statements make Bash scripts more intelligent because they allow scripts to react to different situations.
- File tests, string tests, and numeric tests are important tools for writing useful Bash logic.
- The `case` statement is helpful when checking multiple possible matches in a cleaner way.
- Loops make it possible to repeat tasks without rewriting commands.
- `for` loops and `while` loops are both powerful, but they are useful in different situations.
- Understanding conditions and loops is an important step toward writing more practical Bash automation scripts.

---

## Resources

- Linux and Bash Scripting Guide
- Conditional statements notes
- Loops in Bash notes

---

## Output

Topics covered today:

```bash
Bash conditional statements
if statement
if-else statement
if-elif-else statement
Comparison operators
Combining conditions with AND and OR
case statement
for loop
while loop
Loop control with break
