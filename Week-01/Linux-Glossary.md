# 📚 Linux Glossary

> **🐧 My Personal Linux Dictionary**

Welcome to my Linux Glossary! 👋

This file contains Linux concepts that finally **clicked for me** during my **365-Day Cybersecurity Journey**.

Instead of copying definitions from books or documentation, I'm documenting them in my own words after understanding them through hands-on practice.

Some definitions may look simple—and that's intentional. Future Me should be able to revisit this file six months later and understand every concept in under a minute.

> 💡 **Rule:** If I haven't understood a concept yet, it doesn't belong here.

---

> ⚠️ **Note**
>
> This glossary is intentionally written in simple language.
>
> It reflects **my understanding** of Linux concepts as I learn them through hands-on practice.
>
> The goal isn't to replace official documentation—it's to build a personal knowledge base that I can revisit and continuously improve.
---

# 📂 Navigation

## 📁 Directory

💭 **What I Thought Initially**

I thought a directory was something completely different from a folder.

✅ **What I Know Now**

A directory is simply Linux's name for a **folder**.

Directories are used to organize files and even other directories.

🧪 **Examples**

```text
/home
/etc
/var
```

📝 **Quick Memory**

> Directory = Folder

---

## 📍 Working Directory

💭 **What I Thought Initially**

I thought this meant the location where Ubuntu was installed.

😂 Nope.

✅ **What I Know Now**

A working directory is simply **the place where my terminal is currently standing**.

Whenever I move using `cd`, my working directory changes.

🧪 **Command**

```bash
pwd
```

**Example Output**

```text
/home/cyberadmin
```

🎯 **Memory Trick**

Imagine Google Maps.

The working directory is simply:

> 📍 You are here

---

## 🛣️ Path

✅ **What I Know Now**

A path tells Linux where a file or directory is located.

🧪 **Example**

```text
/home/cyberadmin/Documents
```

📝 **Quick Memory**

Think of it like a home address.

---

## 🏠 Absolute Path

💭 **What I Thought Initially**

I wasn't sure why Linux had different kinds of paths.

✅ **What I Know Now**

An absolute path always starts from the root directory (`/`).

No matter where I currently am, it always points to the same location.

🧪 **Example**

```text
/home/cyberadmin/Documents
```

🎯 **Memory Trick**

Think of it as a complete postal address.

No matter where I stand, the address never changes.

---

## 🚶 Relative Path

💭 **What I Thought Initially**

I thought Linux always required the full path.

✅ **What I Know Now**

A relative path depends on my current working directory.

If I'm already inside:

```text
/home/cyberadmin
```

I can simply type

```bash
cd Documents
```

instead of

```bash
cd /home/cyberadmin/Documents
```

🎯 **Memory Trick**

Relative = Relative to where I'm currently standing.

---

## 🌳 Root Directory

💭 **What I Thought Initially**

I confused the Root Directory with the Root User.

✅ **What I Know Now**

The Root Directory (`/`) is the starting point of the Linux filesystem.

Every file and directory exists somewhere under it.

🧪 **Example**

```text
/
```

📝 **Quick Memory**

Everything starts from `/`.

---

## 🏡 Home Directory

✅ **What I Know Now**

Every user gets a personal workspace called the Home Directory.

Whenever I log in, I usually start here.

🧪 **Example**

```text
/home/cyberadmin
```

---

# 💻 Terminal

## 🖥️ Terminal

💭 **What I Thought Initially**

I thought the terminal was just a black screen for typing commands.

😅

✅ **What I Know Now**

The terminal is my way of communicating with Linux using commands.

Instead of clicking buttons, I tell Linux exactly what I want to do.

---

## ⌨️ Command

✅ **What I Know Now**

A command is simply an instruction I give to Linux.

🧪 **Examples**

```bash
pwd
ls
cd
mkdir
touch
```

---

## 💬 Prompt

💭 **What I Thought Initially**

I never paid attention to it.

✅ **What I Know Now**

The prompt tells me useful information before I type anything.

For example:

```text
cyberadmin@soc-lab-01:~$
```

From this I can identify:

- 👤 Current User
- 💻 Hostname
- 📂 Current Directory

---

# 📄 Files & Filesystem

## 📄 File

✅ **What I Know Now**

A file stores information.

It could be:

- Text
- Images
- Scripts
- Configuration
- Logs

🧪 **Examples**

```text
notes.txt
Lab.md
commands.txt
```

---

## 👻 Hidden File

💭 **What I Thought Initially**

I didn't know Linux had hidden files.

😂

✅ **What I Know Now**

Any file beginning with a `.` is hidden by default.

🧪 **Examples**

```text
.bashrc
.profile
```

To view hidden files:

```bash
ls -a
```

🎯 **Memory Trick**

If the filename starts with a dot...

Linux quietly says:

> 👀 "I'm hiding this unless you ask."

---

## 💾 Filesystem

💭 **What I Thought Initially**

I thought the filesystem meant the hard disk itself.

✅ **What I Know Now**

The filesystem is the way Linux organizes and stores files and directories.

Everything starts from the Root Directory (`/`).

---

# 🧠 Commands I Learned This Week

```text
pwd
ls
ls -a
cd
mkdir
touch
```

---

# ❓Terms I'm Still Curious About

I'll add these only after I genuinely understand them.

- [ ] Kernel
- [ ] Shell
- [ ] Bash
- [ ] Environment Variables
- [ ] File Permissions
- [ ] Owner & Group
- [ ] Processes
- [ ] Services
- [ ] Daemons
- [ ] Package Manager

---

# 🌱 My Progress

## Week 01

✅ Navigation

✅ Files & Directories

✅ Terminal Basics

⬜ Permissions

⬜ Processes

⬜ Services

⬜ Networking

⬜ Shell Scripting

---

💙 **Little Reminder to Future Me**
>
> Don't rush.
>
> The goal isn't to memorize Linux.
>
> The goal is to understand it well enough that one day I can investigate incidents, troubleshoot systems, and confidently work as a cybersecurity professional.
