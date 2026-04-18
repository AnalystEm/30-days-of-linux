# Day 18 - chmod Command in Linux

## Objective

My goal for today was to learn more about the `chmod` command in Linux, especially how it is used to assign, interpret, and restore file permissions using numeric values.

---

## What I Learned

- The `chmod` command is used in Linux and UNIX to modify file and directory permissions.
- It controls who can read, write, or execute a file by setting access rights for the owner, group, and others.
- A command like `chmod 745 newfile.txt` changes the file permissions using numeric notation.
- In the permission value `745`, the owner gets `7`, the group gets `4`, and others get `5`.
- `7` means read, write, and execute.
- `4` means read only.
- `5` means read and execute.
- So a permission like `745` translates to `rwxr--r-x`.
- The owner has full access, the group has read-only access, and others have read and execute access.
- The `chmod` command syntax can include options, a mode, and the file name.
- Permissions in Linux are based on three key types: read, write, and execute.
- The owner, group, and others can each be assigned different permission values.
- Another example shown was `chmod 674 [file_name]`.
- In `674`, the owner has `6`, the group has `7`, and others have `4`.
- `6` means read and write.
- `7` means read, write, and execute.
- `4` means read only.
- This means octal values can be interpreted by breaking each number into its permission combination.
- I also learned about an example permission value of `766`.
- In `766`, the owner has `rwx`, while the group and others both have `rw-`.
- Linux permissions can be reverted by running `chmod` again with the correct permission value.
- For example, a file can be restored to `644`, which means:
  - owner: read and write
  - group: read only
  - others: read only
- A command like `chmod 644 a.txt` restores the file to `rw-r--r--`.

---

## Key Takeaways

- The `chmod` command is very important for managing file and directory security in Linux.
- Numeric permission values make it easier to assign permissions quickly.
- Each number in a chmod command maps directly to permissions for owner, group, and others.
- Understanding values like `644`, `745`, `674`, and `766` helps me read and set permissions more confidently.
- Permission changes are not permanent mistakes because they can be reverted by applying the correct value again.

---

## Resources

- GeeksforGeeks article on the chmod command in Linux
- Notes from previous permission lessons

---

## Output

Topics covered today:

```bash
chmod 745 newfile.txt
chmod 674 [file_name]
chmod 766 filename
chmod 644 a.txt
