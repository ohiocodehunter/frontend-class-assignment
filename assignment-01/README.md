# Assignment 1: Starting a Git Repository

**Student Name:** Karan  
**Roll Number:** [Roll No: To be filled]  
**Course:** B.Tech CSE - Third Year | HTML & CSS Development Lab (BCS554)  
**Institution:** Invertis University, Bareilly  

---

## Aim
Start a Git repository for your lab folder and save your work with commits.

## Tasks & Execution Summary
1. **Task 1: Initialize Git Repository & Set Local Identity**
   - Created folder `html-lab` and ran `git init`.
   - Set local repository identity using `git config --local user.name "Karan"` and `git config --local user.email "karan@invertis.edu"`.
   - Verified settings using `git config user.name` and `git config user.email`.

2. **Task 2: Initial Commit**
   - Created `index.html` with an `<h1>` heading.
   - Checked repository status with `git status` (shows untracked file).
   - Staged file using `git add index.html` and committed with `git commit -m "Add home page"`.

3. **Task 3: Second Commit & Commit History**
   - Added an `<h2>` heading below `<h1>` in `index.html`.
   - Committed changes with `git commit -am "Add next meeting heading"`.
   - Verified commit log with `git log --oneline`.

## Submission
- **Terminal Output:** [terminal-output.txt](terminal-output.txt)
- **HTML File:** [html-lab/index.html](html-lab/index.html)
