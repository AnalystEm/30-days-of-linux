# Day 23 - Understanding the gzip Command in Linux

## Objective

My goal for today was to understand the `gzip` command in Linux, learn how it is used to compress and decompress files, and become familiar with common `gzip` options.

---

## What I Learned

- The `gzip` command in Linux is used to compress files efficiently.
- It helps reduce file size, save disk space, and speed up file transfers.
- `gzip` uses the Lempel-Ziv compression algorithm for speed and efficiency.
- By default, `gzip` compresses a file and replaces it with a `.gz` version of the same name.
- A compressed `.gz` file can be decompressed using `gzip -d` or the `gunzip` command.
- The general syntax is `gzip [options] [filenames]`.
- The `-k` option keeps the original file after compression.
- The `-v` option shows verbose output during compression or decompression.
- The `-f` option forces compression and overwrites an existing `.gz` file if needed.
- `gzip` can compress multiple files in a single command.
- `touch` can be used to create test files before compressing them.

---

## What I Built / Practiced

- Studied how the `gzip` command works in Linux.
- Learned how to compress a file using `gzip`.
- Learned how to decompress a `.gz` file using `gzip -d`.
- Studied how to keep the original file during compression using the `-k` option.
- Learned how to use verbose mode with the `-v` option.
- Learned how to use force compression with the `-f` option.
- Reviewed how multiple files can be compressed in one command.

---

## Challenges Faced

- It took some time to understand that `gzip` usually removes the original file after compression unless the `-k` option is used.
- The difference between normal compression, verbose mode, and force compression needed careful attention.
- Remembering when the original file stays and when it gets replaced was a little confusing at first.

---

## Key Takeaways

- The `gzip` command is a useful Linux tool for file compression and decompression.
- By default, it replaces the original file with a compressed `.gz` file.
- The `-d` option is important for restoring compressed files.
- The `-k`, `-v`, and `-f` options help control how compression works.
- Understanding `gzip` is useful for file storage, backups, and transferring files more efficiently in Linux.

---

## Resources

- GeeksforGeeks Gzip Command in Linux
- Notes from previous Linux command lessons

---

## Output

Topics covered today:

```bash
gzip command
Compressing files
Decompressing .gz files
Keeping the original file with -k
Verbose mode with -v
Force compression with -f
Compressing multiple files
