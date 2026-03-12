# Week 02 Assignment — Python Data Types

## Course
**Advanced Programming** | Sejong University

## Overview
This assignment covers Python's built-in data types including integers, floats, strings, booleans, and type conversion. Students will practice working with variables and understanding how Python handles different kinds of data.

## Files
| File | Description |
|------|-------------|
| `assignment.py` | Your main submission file — complete the TODO sections here |
| `week2-assignment.pdf` | Assignment instructions and problem description |

---

## How to Clone This Repository

Cloning means downloading a copy of this repository to your own computer so you can work on it.

### Step 1 — Install Git
If you don't have Git installed, download it from: https://git-scm.com/downloads  
To check if Git is already installed, open your terminal and run:
```bash
git --version
```
If you see a version number (e.g. `git version 2.39.0`), you're good to go.

### Step 2 — Copy the Repository URL
On the GitHub page for this repository, click the green **Code** button and copy the HTTPS URL. It will look like:
```
https://github.com/sejong-advanced-python/week02-assignment.git
```

### Step 3 — Open Your Terminal
- **Windows**: Search for `Command Prompt` or `Git Bash` in the Start menu
- **Mac**: Open `Terminal` from Applications → Utilities
- **Linux**: Open your terminal application

### Step 4 — Navigate to Your Desired Folder
Use the `cd` command to go to the folder where you want to save the project. For example:
```bash
cd Desktop
```

### Step 5 — Clone the Repository
Run the following command:
```bash
git clone https://github.com/sejong-advanced-python/week02-assignment.git
```
This will create a new folder called `week02-assignment` containing all the files.

### Step 6 — Enter the Project Folder
```bash
cd week02-assignment
```

---

## How to Complete the Assignment

1. Open `assignment.py` in your code editor (e.g. VS Code, PyCharm).
2. Read `week2-assignment.pdf` carefully to understand the problems.
3. Write your code by replacing each `TODO` / `pass` with your solution.
4. Test your code by running it:
```bash
python assignment.py
```

---

## How to Submit (Push to GitHub)

After finishing your assignment, follow these steps to submit it on GitHub.

### Step 1 — Check What Files Changed
```bash
git status
```
You should see `assignment.py` listed as modified.

### Step 2 — Stage Your Changes
This tells Git which files you want to include in your submission:
```bash
git add assignment.py
```
To stage all changed files at once:
```bash
git add .
```

### Step 3 — Commit Your Changes
A commit is like saving a snapshot of your work with a message that describes what you did:
```bash
git commit -m "Complete week02 assignment"
```

### Step 4 — Push to GitHub
This uploads your committed changes to GitHub:
```bash
git push origin main
```

> **If you get a username/password prompt:** GitHub no longer accepts passwords. You need to use a **Personal Access Token (PAT)** instead of your password. Generate one at: https://github.com/settings/tokens

### Step 5 — Verify on GitHub
Go to your GitHub repository page in a browser and confirm that your updated `assignment.py` is visible there.

---

## Full Workflow Summary

```bash
# 1. Clone the repo (only once)
git clone https://github.com/sejong-advanced-python/week02-assignment.git
cd week02-assignment

# 2. Edit assignment.py in your editor, then come back to terminal

# 3. Stage your changes
git add assignment.py

# 4. Commit with a message
git commit -m "Complete week02 assignment"

# 5. Push to GitHub
git push origin main
```

---

## Common Problems and Fixes

| Problem | Fix |
|---------|-----|
| `git: command not found` | Install Git from https://git-scm.com/downloads |
| `Permission denied` | Make sure you are logged in to the correct GitHub account |
| `Authentication failed` | Use a Personal Access Token instead of your password |
| `error: failed to push` | Run `git pull origin main` first, then push again |
| Changes not showing on GitHub | Make sure you ran `git push`, not just `git commit` |

---

## Submission Policy

- Only `assignment.py` will be graded.
- Do **not** modify function signatures or class names unless explicitly instructed.
- Code must be your own work. Plagiarism will result in a grade of zero.

## Academic Integrity
All submitted work must be original. You may discuss approaches with classmates, but your code must be written independently. Sharing or copying code is strictly prohibited.
