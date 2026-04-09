# Day 09 - Linux Directory Structure

## Objective

My goal for today was to understand the Linux directory structure, learn the different file types in Linux, and study the purpose of important top-level directories under the root directory.

---

## What I Learned

- In Linux, many things are treated as files, including normal files, directories, and even devices such as printers and keyboards.
- All directories and files in Linux are stored under a single root directory represented by `/`.
- The Linux directory layout follows the Filesystem Hierarchy Standard.
- This standard helps define how directories are organized and what types of files should be stored in them.
- Linux file types include general files, directory files, and device files.
- General files are ordinary files such as text files, programs, images, and videos.
- Directory files act as containers for other files and subdirectories.
- Device files represent hardware devices in the Linux system.
- In Linux and Unix-like systems, the filesystem begins at the root and follows a tree-like structure.
- Top-level directories under the root each serve a specific role in organizing system files, user data, and configuration files.
- `/bin` contains essential executable programs needed for basic system operation.
- `/etc` stores system-wide configuration files.
- `/home` contains user home directories and is usually the default working location for users.
- `/opt` holds optional or third-party software packages installed separately from the system.
- `/tmp` is used for temporary files and is often cleared on reboot.
- `/usr` contains user-related programs, utilities, and shared resources.
- `/var` stores variable data such as log files that change frequently during system operation.

---

## Key Takeaways

- Linux uses a structured directory layout that begins from the root directory `/`.
- The filesystem hierarchy helps keep the operating system organized and consistent.
- Linux classifies files into different types based on their purpose and usage.
- Understanding top-level directories makes it easier to navigate Linux systems and know where important files are stored.
- Knowing the role of directories like `/bin`, `/etc`, `/home`, `/opt`, `/tmp`, `/usr`, and `/var` gives me a stronger foundation for working in Linux.

---

## Resources

- GeeksforGeeks Linux Directory Structure
- Notes from previous days

---

## Output

Topics covered today:

```bash
Linux directory structure
Types of files in Linux
General files
Directory files
Device files
Root directory
Top-level Linux directories
/bin
/etc
/home
/opt
/tmp
/usr
/var
