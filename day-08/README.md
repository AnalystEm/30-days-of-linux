# Day 08 - Linux File Hierarchy Structure

## Objective

My goal for today was to understand the Linux File Hierarchy Structure, learn how the filesystem hierarchy is organized under the root directory, and study the purpose of some important directories such as `/`, `/bin`, and `/boot`.

---

## What I Learned

- The Linux File Hierarchy Structure, also called the Filesystem Hierarchy Standard, defines the directory structure and directory contents in Unix-like operating systems.
- In Linux, all files and directories appear under the root directory `/`, even if they are stored on different physical or virtual devices.
- The root directory `/` is the top of the Linux filesystem and serves as the base point from which all other directories branch out.
- No directory exists above `/` in the Linux filesystem hierarchy.
- The root directory `/` is not the same as `/root`.
- `/root` is the home directory of the root user, while `/` is the top-level directory of the entire filesystem.
- Only the root user has permission to write directly under the root directory `/`.
- The `/bin` directory contains essential user commands and binary executables needed by all users.
- Common commands such as `ls`, `cp`, `grep`, `ping`, and `ssh` can be found in `/bin`.
- The `/boot` directory stores files required for booting the system.
- `/boot` includes important bootloader files and kernel-related files needed during system startup.
- The Linux directory structure is organized so that each directory has a specific purpose in the system.

---

## Key Takeaways

- The Linux filesystem starts from the root directory `/`, and everything in the system is organized under it.
- Understanding the difference between `/` and `/root` is important because they are not the same directory.
- Directories like `/bin` and `/boot` have very specific roles that support system usage and startup.
- The Linux File Hierarchy Structure helps keep the operating system organized and predictable.
- Learning the purpose of major directories makes it easier to understand and navigate Linux systems.

---

## Resources

- GeeksforGeeks Linux File Hierarchy Structure
- Notes from previous days

---

## Output

Topics covered today:

```bash
Linux File Hierarchy Structure
Filesystem Hierarchy Standard
Root directory
/bin
/boot
Difference between / and /root
