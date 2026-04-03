# Day 03 - Architecture of Linux

## Objective

My goal for today was to understand the architecture of Linux, learn the major layers of the Linux operating system, and understand the role of the kernel and its different types.

---

## What I Learned

- Linux uses a layered architecture where each component has a specific role in the operating system.
- The major components of Linux architecture are Applications, Shell, Kernel, Utilities, and Hardware.
- Applications are the programs users interact with to perform tasks.
- The Shell acts as the interface between the user and the kernel.
- The Kernel is the core component of the Linux operating system and manages communication between software and hardware.
- Utilities provide essential system tools and functions that support user and system operations.
- Hardware forms the physical foundation on which the operating system runs.
- The kernel is responsible for memory management, process management, resource allocation, device management, application interaction, and security.
- A monolithic kernel keeps core operating system services in kernel space and offers high performance, though it can be more complex to maintain.
- A microkernel keeps only essential services in kernel space and runs other services in user space, which improves modularity and security.
- An exokernel exposes hardware resources more directly to applications and offers high flexibility, though it can increase complexity.
- A hybrid kernel combines features of monolithic and microkernel designs to balance performance and flexibility.

---

## What I Built / Practiced

- Studied the layered structure of Linux architecture.
- Learned the functions of the shell, kernel, utilities, applications, and hardware in the Linux operating system.
- Reviewed the responsibilities of the kernel in managing system resources and hardware interaction.
- Learned the differences between monolithic kernel, microkernel, exokernel, and hybrid kernel designs.

---

## Challenges Faced

- It took some time to clearly understand the difference between the shell and the kernel.
- The different kernel types were a bit confusing at first because each one handles system responsibilities in a different way.
- Understanding how all the Linux layers interact with one another required careful reading.

---

## Key Takeaways

- Linux has a structured layered architecture that helps different parts of the system work together efficiently.
- The kernel is the heart of the operating system and is responsible for managing resources and enabling communication between software and hardware.
- The shell is the user-facing interface that helps users interact with the system.
- Different kernel designs exist because operating systems need different balances of performance, security, flexibility, and simplicity.
- Understanding Linux architecture gives me a stronger foundation for learning how Linux works internally.

---

## Resources

- GeeksforGeeks Architecture of Linux
- Notes from previous days

---

## Output

Topics covered today:

```bash
Linux architecture
Linux layers
Kernel responsibilities
Types of kernel
