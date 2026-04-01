# Day 01 - Linux Environment Setup and Basic Navigation

## Objective

My goal for today was to access the Linux VM provided for the challenge, understand how to connect to it from Windows using SSH, set up my working environment, clone the challenge repository, and begin learning the basics of Linux terminal navigation.

---

## What I Learned

* Linux is an operating system that is widely used for servers, cloud systems, and development work.
* SSH is used to connect securely to a remote Linux machine from my local computer.
* The terminal is a text-based interface that lets me interact with the system by typing commands.
* `pwd` shows the current working directory.
* `ls` lists the files and folders in the current directory.
* `cd` is used to move between directories.
* `mkdir` creates a new directory.
* `git clone` copies a remote GitHub repository to my Linux machine.
* `git status` shows the current state of a Git repository.
* A cloned repository does not automatically appear on my own GitHub account until I connect it to my personal repository and push my changes.

---

## What I Built / Practiced

* Connected to the Linux VM using SSH from Windows.
* Confirmed that Command Prompt and Git Bash can both be used for SSH access.
* Created a working directory called `linux_challenge`.
* Cloned the `30-days-of-learning` repository from GitHub.
* Moved into the cloned repository and entered the `day-01` folder.
* Opened the Day 1 template file to understand how to document my learning.
* Practiced and used the following commands:

  * `ssh user14@91.98.230.160`
  * `mkdir linux_challenge`
  * `cd linux_challenge`
  * `pwd`
  * `git clone https://github.com/dataengineering-community/30-days-of-learning.git`
  * `cd 30-days-of-learning`
  * `ls`
  * `git status`
  * `cd day-01`
  * `cat README.md`

---

## Challenges Faced

* At first, I was unsure which terminal to use on Windows and whether CMD would work.
* The first SSH attempt closed before I could log in properly.
* I had trouble pasting or typing the password in the terminal.
* I received a permission denied error when trying to log in.
* After logging in successfully, the server forced a password change and returned an authentication token manipulation error.
* The SSH session disconnected at one point, so I had to reconnect and return to the correct working directory.
* I was also initially unsure whether cloning the repository meant it would automatically appear on my personal GitHub account.

---

## Key Takeaways

* I can now connect to a remote Linux VM from Windows using SSH.
* I understand the difference between my local computer, the remote Linux VM, the cloned repository, and my own GitHub account.
* I know how to create directories and move through the Linux file system.
* I successfully cloned the challenge repository and verified that Git is working inside it.
* I now understand that I need to create and connect my own GitHub repository before my progress can be tracked under my GitHub account.

---

## Resources

* Linux And Bash Scripting Guide
* Linux Tutorial
* 50 Most Popular Linux and Terminal Commands
* Repo Cloning Guide
* Challenge Guideline

---

## Output

Commands used today:

```bash
ssh user14@91.98.230.160
mkdir linux_challenge
cd linux_challenge
pwd
git clone https://github.com/dataengineering-community/30-days-of-learning.git
cd 30-days-of-learning
pwd
ls
git status
cd day-01
pwd
ls
cat README.md
