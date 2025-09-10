### **Unix Commands & Shell Basics**

* What does the `ls` command really show? (hidden files, options like `-l` and `-h`)
* The difference between `>` and `>>` when redirecting output
* How `|` (pipes) let you chain commands together
* Using `grep` to find things in large files
* `head` vs `tail`: when you’d use each in analyzing data
* Wildcards (`*`, `?`) for file matching
* Why relative paths (`../`) and absolute paths (`/home/user/...`) matter

---

### **Working on a High-Performance Cluster**

* What is a “login node” vs. a “compute node”?
* The purpose of a job scheduler (e.g., SLURM, PBS)
* Anatomy of a simple job script (`#!/bin/bash`, resources, commands)
* Why HPC clusters use **modules** (e.g., `module load python`)
* What environment variables are and why `$PATH` matters
* Parallel vs. serial jobs: what’s the difference?

---

### **Practical Data Handling**

* Compressing and uncompressing files with `gzip`/`gunzip`
* Viewing huge files safely with `less`
* Counting lines, words, or characters with `wc`
* Finding the size of files with `du` and `ls -lh`
* Renaming batches of files with `mv` and wildcards

---

### **Good Practices & Tips**

* Why documentation (`man` pages) are your best friend
* The importance of comments in shell scripts
* Organizing project directories (e.g., `raw_data/`, `scripts/`, `results/`)
* The difference between running something interactively vs. submitting it as a batch job

---
Perfect! Here’s a **ready-to-use assignment list** of short presentation topics (about 2 minutes each). You can copy/paste and hand this out so students can pick a topic:

---

## 🎤 Short Presentation Topics: UNIX & HPC Basics

Each student will prepare a **2-minute presentation** explaining one of the following topics. Your goal is to:

1. **Define** the command or concept.
2. **Demonstrate** a simple example (show input and output).
3. **Explain** when/why it’s useful for working with big data on an HPC cluster.

---

### **Unix Commands**

1. **The `ls` command**: Listing files, using options like `-l` and `-h`.
2. **Hidden files**: What they are and how `ls -a` reveals them.
3. **`cd` and paths**: Relative vs. absolute paths.
4. **Redirection**: `>` vs `>>` for saving command output.
5. **Pipes (`|`)**: Chaining commands together.
6. **`grep`**: Searching inside files for patterns.
7. **`head` and `tail`**: Previewing parts of large files.
8. **Wildcards**: Using `*` and `?` to match filenames.
9. **`wc`**: Counting lines, words, and characters.
10. **`less`**: Safely viewing huge files without crashing your terminal.

---

### **HPC Basics**

11. **Login node vs. compute node**: Why you shouldn’t run jobs on the login node.
12. **Job schedulers**: What SLURM (or PBS, depending on your system) does.
13. **Anatomy of a job script**: `#!/bin/bash`, requesting CPUs, memory, and time.
14. **Interactive jobs vs. batch jobs**: When to use each.
15. **Modules**: How `module load` gives you access to software.
16. **Environment variables**: What `$PATH` is and why it matters.

---

### **Data Management & Good Practices**

17. **Compressing files**: Using `gzip` and `gunzip`.
18. **File sizes**: Using `du` and `ls -lh`.
19. **Organizing project directories**: A tidy layout (`raw_data/`, `scripts/`, `results/`).
20. **`man` pages**: How to find help and understand command options.

<img width="468" height="649" alt="image" src="https://github.com/user-attachments/assets/7871d9c4-f9ef-401b-9287-d5fba359bf1d" />
