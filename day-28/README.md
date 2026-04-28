# Day 28 - Scheduling and Automation with Cron

## Objective

My goal for today was to understand how scheduling and automation work in Linux using cron, learn how cron jobs are structured, and study how scripts can be scheduled, tested, and monitored more reliably.

---

## What I Learned

- Scheduling and automation are important in data engineering because manual execution does not scale well and automation improves consistency, reliability, and timeliness.
- Cron is a time-based job scheduler in Unix and Linux systems.
- The cron daemon runs in the background and checks scheduled jobs automatically.
- Cron jobs are defined in a crontab file.
- A cron expression is made up of fields for minute, hour, day of month, month, and day of week, followed by the command to run.
- Cron can be used to schedule jobs daily, weekly, hourly, every few minutes, or during selected days and hours.
- Example schedules include running a job every day at midnight, every Monday at 2:30 AM, every 15 minutes, every 6 hours, or every hour between 9 AM and 5 PM on weekdays.
- The `crontab -l` command is used to view the current crontab.
- The `crontab -e` command is used to edit the user’s crontab.
- The `crontab -r` command removes all cron jobs for the current user.
- A script should be made executable with `chmod +x` before scheduling it with cron.
- A cron job can be scheduled by adding a cron expression followed by the full script path.
- Cron jobs run silently by default, so it is useful to redirect output and errors to a log file.
- `>>` appends output to a log file.
- `2>&1` redirects errors to the same file as standard output.
- It is important to test a script manually before scheduling it with cron.
- A script can also be tested in a cron-like environment using `bash -l -c`.
- Best practices for cron jobs include using logs, testing scripts first, using absolute paths, avoiding overlapping jobs, monitoring job success or failure, and rotating old logs.

---

## What I Built / Practiced

- Studied how cron works in Linux for scheduling tasks.
- Learned how cron expressions are structured and how each field controls scheduling.
- Reviewed common examples of cron schedules.
- Learned the commands used to view, edit, and remove crontab entries.
- Studied how to schedule a Bash script with cron.
- Learned how to redirect cron output and errors to a log file.
- Reviewed how to test scripts before scheduling them.
- Learned important best practices for making cron jobs more reliable.

---

## Challenges Faced

- It took some time to understand the cron time format and what each field represents.
- Some schedule examples looked similar at first, so I had to pay attention to how the minute, hour, and weekday fields change the behavior.
- I needed to read carefully to understand why absolute paths and log redirection are important when using cron.
- The difference between running a script manually and running it through cron needed extra attention.

---

## Key Takeaways

- Cron is a powerful Linux tool for automating scripts at scheduled times.
- Cron jobs are defined using a structured time format in the crontab file.
- Scripts should always be tested and made executable before scheduling them.
- Logging is very important because cron jobs do not show output on the screen by default.
- Using absolute paths, monitoring failures, and avoiding job overlap are important cron best practices.
- Understanding cron makes it easier to automate recurring data engineering tasks reliably.

---

## Resources

- Linux and Bash Scripting Guide
- Scheduling and automation with cron notes
- Cron command examples and best practices

---

## Output

Topics covered today:

```bash
Cron scheduling
Crontab structure
Cron expressions
Managing cron jobs
Scheduling Bash scripts
Redirecting cron logs
Testing cron jobs
Cron best practices
