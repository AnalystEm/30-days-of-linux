# Day 11 - Absolute and Relative Pathnames in Linux

## Objective

My goal for today was to understand how paths work in Linux, learn the difference between absolute and relative paths, and understand how special symbols like `.` and `..` are used in navigation.

---

## What I Learned

- In Linux, a path is used to specify the exact location of a file or directory inside the filesystem.
- Paths are important for file navigation, command execution, scripting, and system administration.
- Linux mainly uses two types of paths: absolute path and relative path.
- An absolute path gives the full and exact location of a file or directory starting from the root directory `/`.
- An absolute path does not depend on the current working directory.
- Absolute paths always begin with a forward slash `/`.
- They are reliable because they always point to the same location in the system.
- A relative path gives the location of a file or directory with respect to the current working directory.
- A relative path does not start from the root directory.
- Relative paths depend on where I currently am in the filesystem.
- Relative paths are usually shorter and easier to type, but their meaning changes if the current directory changes.
- In relative paths, `.` refers to the current directory.
- In relative paths, `..` refers to the parent directory.
- Relative and absolute paths can both be used to change directories, but they work differently depending on context.

---

## Key Takeaways

- Absolute paths always start from the root directory and give the full location of a file or folder.
- Relative paths depend on the current working directory and are often shorter to use.
- The symbols `.` and `..` are very useful for moving around the Linux filesystem.
- Understanding the difference between absolute and relative paths makes directory navigation much easier.
- This topic is important because paths are used constantly in Linux commands, scripts, and system operations.

---

## Resources

- GeeksforGeeks Absolute and Relative Pathnames in Linux
- Notes from previous days

---

## Output

Topics covered today:

```bash
Absolute paths
Relative paths
Pathnames in Linux
Current directory
Parent directory
Using . and ..
