# Day 01 - Linux Navigation & Basic File Operations

**Date:** July 26, 2026

---

# Introduction

Although I have used Linux before while working with cybersecurity tools like Wazuh, I realised that I was mostly following commands without understanding the concepts behind them.

This journey is about building strong Linux fundamentals by understanding **why** things work, not just **how** to run commands.

Today's goal was to get comfortable navigating the Linux terminal and performing basic file operations.

---

# Practical 1 - Finding My Current Working Directory

## Command

```bash
pwd
```

## Output

```text
/home/cyberadmin
```

## What I Learned

The `pwd` command shows my current working directory.

I understood that the terminal is always working inside one directory, and `pwd` simply tells me where I am.

---

# Practical 2 - Listing Files and Directories

## Command

```bash
ls
```

## Output

```text
Desktop
Documents
Downloads
Music
Pictures
Public
Templates
Videos
```

## What I Learned

The `ls` command lists everything inside the current directory.

Initially, I expected it to show the entire Linux filesystem, but I realised it only displays the contents of my current location.

---

# Practical 3 - Creating My Cybersecurity Workspace

## Command

```bash
mkdir cybersecurity365
```

## Verification

```bash
ls
```

## Output

```text
cybersecurity365
```

## What I Learned

`mkdir` creates a new directory.

I also realised that Linux immediately creates the folder if the command is valid and I have permission.

---

# Practical 4 - Moving Between Directories

## Commands

```bash
cd cybersecurity365
pwd
```

## Output

```text
/home/cyberadmin/cybersecurity365
```

## What I Learned

`cd` changes my current directory.

Using `pwd` immediately afterwards helped me confirm that my location had changed.

---

# Practical 5 - Organizing My Project

## Commands

```bash
mkdir Week-01
mkdir notes
mkdir scripts
mkdir tools
mkdir logs
```

## Verification

```bash
ls
```

## Output

```text
Week-01
logs
notes
scripts
tools
```

## What I Learned

Creating folders from the beginning keeps the project organized and makes it easier to manage as it grows.

---

# Practical 6 - Creating Empty Files

## Commands

```bash
touch linux_notes.md
touch commands.txt
```

## Verification

```bash
ls
```

## Output

```text
commands.txt
linux_notes.md
```

## What I Learned

The `touch` command creates an empty file instantly without opening a text editor.

---

# Practical 7 - Viewing Hidden Files

## Command

```bash
ls -a
```

## Output

```text
.
..
.bashrc
.profile
.cache
...
```

## What I Learned

I noticed several files beginning with a `.` that were hidden when I used the normal `ls` command.

Linux treats files and directories starting with a `.` as hidden.

---

# Practical 8 - Returning to My Home Directory

## Commands

```bash
cd ~
pwd
```

## Output

```text
/home/cyberadmin
```

## What I Learned

The `~` symbol always represents my home directory, making it an easy way to return there from anywhere in the filesystem.

---

# Commands Practiced

```text
pwd
ls
ls -a
cd
mkdir
touch
```

---

# Reflection

Today's session wasn't about learning many commands—it was about understanding how Linux navigation works.

Even though I had used these commands before during work, I realised I never really understood how they worked together.

After experimenting with `pwd`, `ls`, and `cd`, navigating the Linux terminal started feeling much more natural.

---

# Questions for Tomorrow

- Why does Linux start from `/` instead of using drive letters like Windows?
- What is a working directory?
- What is the difference between an absolute path and a relative path?
- Why are some files hidden by default?
