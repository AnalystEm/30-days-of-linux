# Day 15 - Directory Management in Linux

## Objective

My goal for today was to understand directory management in Linux and learn how to create, list, remove, navigate, copy, move, and rename directories using common Linux commands.

---

## What I Learned

- Directories in Linux are special types of files that store references to other files and directories in a hierarchical structure.
- Directories act as containers for files and subdirectories.
- The root directory `/` is the top-level directory in Linux.
- Special directories like `.` for the current directory and `..` for the parent directory are useful for navigation.
- The `mkdir` command is used to create a new directory.
- The `ls` command is used to list directories, and `ls -l` gives a more detailed view of items in a directory.
- Entries that begin with `d` in `ls -l` output represent directories.
- The contents of a directory can be listed by using `ls path/to/directory`.
- The `rmdir` command is used to remove an empty directory.
- To remove a directory that contains files or subdirectories, `rm -rf` can be used.
- The `cd` command is used to move from one directory to another.
- `cd -` moves back to the previous directory.
- `cd ..` moves to the parent directory.
- `cd ~` returns to the home directory.
- `cd .` refers to the current directory.
- The `cp -r` command is used to copy a directory and all of its contents recursively.
- The `mv` command is used to move or rename directories.

---

## Key Takeaways

- Directory management is an important part of working in Linux because directories help organize the file system.
- Commands like `mkdir`, `ls`, `cd`, `rmdir`, `rm -rf`, `cp -r`, and `mv` are essential for managing directories effectively.
- Understanding special directory symbols like `.`, `..`, and `~` makes navigation easier.
- It is important to be careful with commands like `rm -rf` because they can permanently remove directories and their contents.
- Learning how to create, inspect, copy, move, and remove directories gives me more confidence in working with Linux.

---

## Resources

- GeeksforGeeks Directory Management in Linux
- Notes from previous days

---

## Output

Topics covered today:

```bash
Directory management in Linux
mkdir
ls
ls -l
rmdir
rm -rf
cd
cd -
cd ..
cd ~
cd .
cp -r
mv
