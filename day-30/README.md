Here is the raw Markdown content based on your template from **image_e2757e.png**, **image_e2755b.png**, and **image_e223bf.png**. You can copy and paste this directly into your GitHub `README.md`.

---

# Day 30 - Bash Best Practices & Security[cite: 1]

## Objective

**What was the goal for today?**
To move beyond basic scripting and learn professional standards for writing clean, maintainable, and secure Bash code for Linux environments[cite: 1].

---

## What I Learned

*   **Google Shell Style Guide:** Adopting industry standards like using `local` variables in functions, naming constants in `CAPS`, and preferring `[[ ... ]]` over `[ ... ]` for tests[cite: 1].
*   **Linting with ShellCheck:** Using static analysis tools to catch syntax errors, non-portable code, and common logic bugs before execution[cite: 1].
*   **Defensive Scripting:** Implementing the "Safety Header" (`set -euo pipefail`) to ensure scripts exit immediately on errors, unset variables, or pipe failures[cite: 1].
*   **Security & Injection Attacks:** Understanding why `eval` is dangerous and why quoting variables (`"$VAR"`) is mandatory to prevent command injection[cite: 1].
*   **Handling Secrets:** Strategies for managing passwords and sensitive data using `read -s` and restricted file permissions (`chmod 600`) instead of hardcoding[cite: 1].

---

## What I Built / Practiced

*   Refactored a standard script to include a professional "safety header"[cite: 1].
*   Practiced function scoping by converting global variables to `local` within logic blocks[cite: 1].
*   Tested scripts against `ShellCheck` to identify and fix style warnings[cite: 1].

---

## Challenges Faced

*   Understanding the technical difference between `[` and `[[` and why the latter is safer in Bash[cite: 1].
*   Developing the habit of quoting every single variable to prevent word-splitting and globbing issues[cite: 1].

---

## Key Takeaways

*   **Fail Early:** It is better for a script to exit immediately than to continue running in an unpredictable or dangerous state[cite: 1].
*   **Quote Everything:** Double quotes around variables are the simplest and most effective way to prevent most Bash security vulnerabilities[cite: 1].
*   **Don't Trust User Input:** Never use `eval` or unquoted variables with data provided by an external source[cite: 1].

---

## Resources

*   [Google Shell Style Guide](https://google.github.io/styleguide/shellguide.html)[cite: 1]
*   [ShellCheck: Static Analysis Tool](https://www.shellcheck.net/)[cite: 1]
*   Linux Manual Pages (`man bash`)[cite: 1]

---

## Output

### Secure Script Template
```bash
#!/bin/bash
# Safety Header: Exit on error, unset vars, and pipe failures
set -euo pipefail

# Constants
readonly LOG_FILE="/tmp/script.log"

# Functions
cleanup() {
    local exit_code=$?
    echo "Script exiting with status: $exit_code"
}

# Trap to execute cleanup on exit
trap cleanup EXIT

main() {
    local user_input="$1"
    echo "Processing safely: $user_input"
}

main "${1:-default_value}"
