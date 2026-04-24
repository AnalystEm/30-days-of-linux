# Day 24 - Introduction to Bash Scripting, Variables, and User Input

## Objective

My goal for today was to understand the basics of Bash scripting, learn how Bash scripts are structured and executed, and study how variables, user input, environment variables, and read-only variables work in Bash.

---

## What I Learned

- Bash scripting is a way to automate Linux commands by writing them in a script file.
- A Bash script is simply a text file that contains a series of commands that can run automatically.
- A typical Bash script begins with a shebang line such as `#!/bin/bash`, which tells the system to use the Bash interpreter.
- Bash scripts can include comments, commands, and logic.
- The `echo` command prints text to the terminal.
- Command substitution using `$(command)` allows the output of a command to be stored or used inside another command.
- A script file can be made executable using `chmod +x filename.sh`.
- A Bash script can be run using `./filename.sh`.
- Variables in Bash are placeholders used to store values such as names, roles, paths, and user input.
- Variables are defined without spaces around the `=` sign.
- Variable values are accessed using `$variable`.
- Quoting variables like `"$name"` helps handle spaces safely.
- The `read` command is used to collect input from the user.
- Environment variables are built-in variables provided by the system, such as `$USER`, `$HOME`, `$PWD`, `$HOSTNAME`, and `$SHELL`.
- Variables can be exported with `export` to make them available to child processes or other scripts.
- The `readonly` keyword makes a variable constant so it cannot be changed later.
- Common mistakes in Bash scripting include forgetting the shebang line, forgetting `chmod +x`, using Windows line endings, and not quoting variables.

---

## What I Built / Practiced

- Studied the purpose and structure of a Bash script.
- Learned how to create a simple Bash script and how it runs.
- Reviewed how to make a script executable with `chmod +x`.
- Learned how variables are created and referenced in Bash.
- Studied command substitution using `$(date)`.
- Learned how to take user input with the `read` command.
- Reviewed common environment variables used in Bash.
- Learned how to export variables and create read-only variables.

---

## Challenges Faced

- It took some time to understand the difference between normal variables, environment variables, and exported variables.
- I had to pay attention to the rule that there should be no spaces around the `=` sign when assigning variables.
- The difference between writing a script and making it executable needed careful understanding.
- Some of the common mistakes, like line endings and quoting variables, were easy to overlook at first.

---

## Key Takeaways

- Bash scripting is a practical way to automate repetitive Linux tasks.
- Every Bash script should start with a proper shebang line.
- Variables make scripts more flexible and reusable.
- The `read` command allows scripts to interact with users.
- Environment variables help scripts adapt to the system they are running on.
- `export` makes a variable available outside the current shell, while `readonly` protects a variable from being changed.
- Understanding these basics gives me a strong foundation for writing more useful Bash scripts later.

---

## Resources

- Linux and Bash Scripting Guide
- Bash scripting overview notes
- Variables and user input notes

---

## Output

Topics covered today:

```bash
Bash scripting
Structure of a Bash script
Variables in Bash
Command substitution
Reading user input
Environment variables
Exporting variables
Read-only variables
Common Bash mistakes
