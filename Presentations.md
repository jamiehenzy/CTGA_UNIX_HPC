You work with labmates who know absolutely nothing about UNIX commands and high-performance computing, so they rely on you to explain some basic concepts and demonstrate basic skills. Your job is to prepare a **2-minute presentation** explaining one of the following topics:

1. **Define** the command or concept.
2. **Demonstrate** a simple example (show input and output).
3. **Explain** when/why it’s useful for working with big data on an HPC cluster.

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



