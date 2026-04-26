# Day 26 - Functions and Reusability in Bash

## Objective

My goal for today was to understand how functions work in Bash, learn how they improve code reusability, and study how parameters, return values, local variables, and sourced utility functions can make Bash scripts cleaner and more modular.

---

## What I Learned

- Functions in Bash are reusable named blocks of code that perform a specific task.
- They help reduce repetition and make scripts cleaner, easier to manage, and easier to maintain.
- A function can be defined using `function name {}` or `name() {}` syntax.
- Functions must be defined before they are called in a script.
- Functions can be called multiple times after they are defined.
- Functions can accept parameters, and arguments are accessed using `$1`, `$2`, `$3`, and so on.
- `$@` represents all arguments passed to a function.
- Functions in Bash can return a status code using `return`.
- A return status of `0` usually means success, while non-zero values usually indicate failure.
- `$?` is used to capture the exit status of the last executed command or function.
- Variables inside Bash functions are global by default unless they are declared with `local`.
- The `local` keyword is used to create function-specific variables and avoid naming conflicts.
- Functions can return data by printing output and capturing it with command substitution.
- Multiple functions can be combined to create modular workflows, such as ETL-style scripts with separate extract, transform, and load functions.
- Utility functions can be stored in a separate file and imported into another script using `source`.

---

## What I Built / Practiced

- Studied how functions are defined and called in Bash.
- Learned how functions can receive parameters and use them in script logic.
- Reviewed how return values and exit codes work in Bash functions.
- Learned the difference between global variables and local variables inside functions.
- Studied how functions can return data through command substitution.
- Reviewed how multiple functions can work together in a workflow.
- Learned how reusable utility functions can be sourced from another file.

---

## Challenges Faced

- It took some time to understand the difference between returning a status code and returning actual data from a function.
- The use of `$1`, `$2`, `$@`, and `$?` needed careful attention.
- I had to pay close attention to when a variable is global by default and when to use `local`.
- The idea of sourcing functions from another file was new, so I needed to read through it carefully.

---

## Key Takeaways

- Functions make Bash scripts more organized and reusable.
- Parameters allow functions to handle different inputs without rewriting the same code.
- Exit codes are important for checking whether a function succeeded or failed.
- The `local` keyword helps prevent variable conflicts inside larger scripts.
- Functions can be combined to build cleaner and more modular workflows.
- Using `source` makes it possible to reuse utility functions across multiple scripts.

---

## Resources

- Linux and Bash Scripting Guide
- Bash functions notes
- Reusability and workflow automation notes

---

## Output

Topics covered today:

```bash
Bash functions
Function parameters
Return values and exit codes
Local variables
Returning data from functions
Workflow automation with functions
Sourcing functions from another file
