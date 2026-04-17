# Day 17 - Changing Permissions in Linux

## Objective

My goal for today was to learn how to change permissions in Linux using the `chmod` command, and to understand both symbolic notation and octal notation for managing file access.

---

## What I Learned

- Linux permissions can be modified using the `chmod` command, which stands for change mode.
- File permissions can be changed using symbolic notation or octal notation.
- Symbolic notation allows permissions to be added, removed, or set for specific users.
- In symbolic notation, `u` stands for user, `g` stands for group, and `o` stands for others.
- The `+` operator is used to add permissions.
- The `-` operator is used to remove permissions.
- The `=` operator is used to set permissions to a specific value.
- An example like `chmod o+x xyz.txt` adds execute permission for others to the file.
- A command like `chmod ugo-rwx xyz.txt` removes read, write, and execute permissions from user, group, and others.
- Another example like `chmod ug+rw,o-x abc.mp4` adds read and write permission to user and group and removes execute permission from others.
- Octal notation represents permissions with numbers for user, group, and others.
- In octal notation, read `r` equals 4, write `w` equals 2, and execute `x` equals 1.
- These values are added together to produce a permission number for each category.
- Octal values from 0 to 7 represent different permission combinations.
- A permission set like `rw- r-x r--` means the owner can read and write, the group can read and execute, and others can only read.

---

## Key Takeaways

- The `chmod` command is essential for changing file permissions in Linux.
- Symbolic notation is useful when I want to add, remove, or set permissions clearly for specific users or groups.
- Octal notation provides a compact way to assign permissions using numbers.
- Understanding the values of `r`, `w`, and `x` makes octal permissions easier to read and use.
- Learning both symbolic and octal notation gives me more confidence in managing Linux file security.

---

## Resources

- GeeksforGeeks Linux Permissions
- Notes from previous days

---

## Output

Topics covered today:

```bash
chmod
symbolic notation
octal notation
u g o
+ - =
r = 4
w = 2
x = 1
rw- r-x r--
