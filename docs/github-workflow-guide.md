# GitHub & VS Code Workflow Guide (Mac)

This guide explains how to:

* clone the repository
* open it in VS Code
* create/update files
* save changes to GitHub

---

# 1. Install Requirements

## Install Git

Download:

[Git Downloads](https://git-scm.com/downloads/mac?utm_source=chatgpt.com)

Verify installation in Terminal:

```bash
git --version
```

---

## Install VS Code

Download:

[Visual Studio Code](https://code.visualstudio.com/?utm_source=chatgpt.com)

---

# 2. Clone The Repository

Open Terminal.

Move to the folder where you want the project:

```bash
cd ~/Documents
```

Clone the repository:

```bash
git clone https://github.com/Lifleikur/homework.git
```

Move into the project:

```bash
cd homework
```

Open the project in VS Code:

```bash
code .
```

If `code .` does not work:

1. Open VS Code
2. Press:

   * Cmd + Shift + P
3. Search:

   * Shell Command: Install 'code' command in PATH
4. Press Enter
5. Retry:

   ```bash
   code .
   ```

---

# 3. Create A New File

Inside VS Code:

1. Open the Explorer sidebar
2. Right click a folder
3. Select:

   * New File
4. Example:

   ```text
   docs/my-notes.md
   ```

VS Code automatically creates:

* the file
* the folder path if needed

---

# 4. Save Changes

Save file:

```text
Cmd + S
```

---

# 5. Check Git Status

In VS Code terminal:

```bash
git status
```

This shows changed/new files.

---

# 6. Add Changes

Stage all files:

```bash
git add .
```

---

# 7. Create A Commit

Example:

```bash
git commit -m "Add QA learning notes"
```

Good commit messages:

* Add bug report examples
* Update LinkedIn roadmap
* Add API testing notes
* Add Cypress examples

---

# 8. Push Changes To GitHub

Upload changes:

```bash
git push
```

---

# 9. Pull Latest Changes

Before starting work each day:

```bash
git pull
```

This downloads the newest updates from GitHub.

---

# Basic Workflow Summary

## Start Working

```bash
git pull
```

## After Making Changes

```bash
git add .
git commit -m "Describe changes"
git push
```

---

# Important Notes

* GitHub does NOT track empty folders
* Files must exist inside folders for Git to upload them
* Save files before committing
* Small commits are better than huge commits
* Commit often while working

---

# Goal Of This Repository

This repository is intended to:

* build a professional QA portfolio
* document learning progress
* showcase practical QA skills
* support LinkedIn and CV improvements
* demonstrate ongoing technical engagement
