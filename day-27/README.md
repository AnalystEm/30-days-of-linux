# Day 27 - Error Handling and Debugging in Bash

## Objective

My goal for today was to understand how error handling and debugging work in Bash, learn how to write safer scripts, and study the tools Bash provides for detecting failures, stopping on errors, and troubleshooting script behavior.

---

## What I Learned

- Error handling is important in Bash because a script can continue running even after a command fails if errors are not handled properly.
- Poor error handling can lead to misleading success messages, overwritten files, silent failures, or corrupted processing.
- Every command in Bash returns an exit status code.
- An exit code of `0` means success, while a non-zero exit code means failure.
- The special variable `$?` stores the exit status of the last executed command.
- Exit codes can be used inside conditional statements to check whether a command succeeded before taking the next step.
- The `set -e` option makes Bash exit immediately if any command fails.
- `set -e` helps prevent scripts from continuing after an unexpected error.
- The `exit` command can be used to stop a script manually and return a custom exit code.
- Custom error messages can be printed before exiting so the reason for failure is clear.
- Some common exit codes are `0` for success, `1` for general error, `2` for misuse of shell builtins, `126` for command invoked cannot execute, `127` for command not found, and `130` for script terminated by `Ctrl + C`.
- The `trap` command is another tool for more advanced error handling.
- The `set -x` option enables debug mode and prints commands as they are executed.
- The `set +x` option disables debug mode.
- Debug mode is useful for tracing script behavior and troubleshooting failures.
- The `set -u` option causes Bash to throw an error if an undefined variable is used.
- `set -u` helps catch small bugs caused by missing variable values.
- Multiple safety options can be combined using `set -euo pipefail` for more robust scripts.
- Logging and monitoring are important for understanding what happens in production scripts and for reviewing failures later.

---

## What I Built / Practiced

- Studied why error handling is necessary in Bash scripts.
- Learned how exit codes work and how to inspect them with `$?`.
- Reviewed how to use conditional logic to respond to command success or failure.
- Learned how `set -e` can stop scripts on error.
- Studied how to use `exit` to return custom errors.
- Reviewed common Bash exit code meanings.
- Learned how to use `set -x` for debugging and `set +x` to turn it off.
- Studied how `set -u` catches undefined variables.
- Learned how safety options can be combined with `set -euo pipefail`.

---

## Challenges Faced

- It took some time to understand the difference between a command failing silently and a script stopping immediately.
- I had to pay close attention to what each safety option does and when it should be used.
- Exit codes were a little confusing at first because different non-zero values can mean different types of errors.
- The debugging options were clear in concept, but I needed to read carefully to understand how they help during troubleshooting.

---

## Key Takeaways

- Error handling is essential for writing safe and reliable Bash scripts.
- Exit codes help determine whether commands succeed or fail.
- `set -e` prevents a script from continuing after an unexpected failure.
- `set -x` is useful for debugging because it shows each command as it runs.
- `set -u` helps catch undefined variable mistakes early.
- Combining safety options with `set -euo pipefail` makes scripts more robust.
- Logging and monitoring are important for diagnosing issues in real workflows.

---

## Resources

- Linux and Bash Scripting Guide
- Error handling and debugging notes
- Bash safety options notes

---

## Output

Topics covered today:

```bash
Error handling in Bash
Exit codes
Using $? in Bash
Stopping scripts with set -e
Custom exits with exit
Debug mode with set -x
Undefined variable checks with set -u
Combining safety options with set -euo pipefail
Logging and monitoring
