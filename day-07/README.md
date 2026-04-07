# Day 07 - Linux File System

## Objective

My goal for today was to understand the Linux file system, learn how files and directories are organized in Linux, and study the main layers of the file system structure.

---

## What I Learned

- The Linux file system is a structured way of storing and organizing data on a Linux machine.
- In Linux, all files and directories begin from a single root directory `/`.
- The Linux file system follows a hierarchical tree structure, which makes file navigation organized and logical.
- Important directories such as `/home`, `/etc`, `/bin`, and `/var` each serve specific system purposes.
- Linux supports multiple file system types such as ext4, XFS, and Btrfs.
- The Linux file system architecture is organized into three important layers.
- The logical file system acts as the interface between user applications and the file system.
- The logical file system handles file operations such as open, read, write, and close.
- The logical file system also provides security checks such as permissions and file access control.
- The virtual file system provides a common interface for different file systems and allows Linux to support multiple file system types at the same time.
- The virtual file system acts as an abstraction layer that hides the internal details of each file system.
- The physical file system interacts directly with hardware and disk storage.
- The physical file system manages data blocks, inodes, and physical memory allocation.
- The physical file system is responsible for writing data to disk and retrieving it efficiently.

---

## Key Takeaways

- The Linux file system starts from the root directory and is organized in a clear tree structure.
- Different Linux directories have different purposes and help organize the system properly.
- The file system is not just about folders and files, but also about how Linux manages access, storage, and compatibility.
- The logical file system, virtual file system, and physical file system each play a different role in how data is managed.
- Understanding the Linux file system gives me a stronger foundation for navigating and working with Linux systems.

---

## Resources

- GeeksforGeeks Linux File System
- Notes from previous days

---

## Output

Topics covered today:

```bash
Linux file system
Root directory
Hierarchical directory structure
Logical file system
Virtual file system
Physical file system
