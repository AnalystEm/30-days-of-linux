# Day 16 - Linux Permissions

## Objective

My goal for today was to understand Linux permissions, learn the three basic permission types, and study how permissions are assigned to owners, groups, and other users in the system.

---

## What I Learned

- Linux file permissions are part of the system’s security model and define who can read, write, or execute files and directories.
- Permissions help ensure that only authorized users or processes can access or modify data.
- The three basic permissions in Linux are read, write, and execute.
- Read permission, written as `r`, allows a user to view a file’s contents or list a directory’s files.
- Write permission, written as `w`, allows a user to modify a file or add and delete files in a directory.
- Execute permission, written as `x`, allows a file to run as a program or script, or allows a user to enter a directory.
- Permissions are assigned to three categories of users: user or owner, group, and others.
- The user or owner is the person who created or owns the file.
- The group refers to users who belong to the same shared group.
- Others refers to everyone else on the system.
- Linux permission operators include `+`, `-`, and `=`.
- The `+` operator is used to add permissions.
- The `-` operator is used to remove permissions.
- The `=` operator is used to set permissions to a specified value.
- Permissions are commonly managed with the `chmod` command.
- Examples of permission changes include `chmod +rwx filename`, `chmod -rwx directoryname`, `chmod +x filename`, and `chmod -wx filename`.

---

## Key Takeaways

- Linux permissions are important because they control access to files and directories and help protect the system.
- The three basic permissions, `r`, `w`, and `x`, each serve a different purpose.
- Permissions are not applied the same way to everyone, because Linux separates users into owner, group, and others.
- Operators like `+`, `-`, and `=` make it possible to add, remove, or set permissions as needed.
- Understanding permissions is an important step toward using Linux more safely and confidently.

---

## Resources

- GeeksforGeeks Linux Permissions
- Notes from previous days

---

## Output

Topics covered today:

```bash
Linux permissions
Read permission
Write permission
Execute permission
Owner
Group
Others
chmod
+ operator
- operator
= operator
