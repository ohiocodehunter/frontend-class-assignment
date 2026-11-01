# Assignment 2: Pushing and Cloning a Repository

**Student Name:** Karan  
**Roll Number:** [Roll No: To be filled]  
**Course:** B.Tech CSE - Third Year | HTML & CSS Development Lab (BCS554)  
**Institution:** Invertis University, Bareilly  

---

## Aim
Send your commits to a second repository on your computer and make a copy of it with clone.

## Tasks & Execution Summary
1. **Task 1: Create Bare Remote Repository**
   - Inside `html-lab`, initialized an empty bare repository: `git init --bare ../html-remote`.
   - Added remote: `git remote add origin ../html-remote`.
   - Verified remotes with `git remote -v`.

2. **Task 2: Push Commits to Origin**
   - Pushed main branch to origin using `git push origin main`.

3. **Task 3: Clone Remote Repository**
   - Navigated up one directory (`cd ..`).
   - Cloned `html-remote` into `html-copy` using `git clone html-remote html-copy`.
   - Navigated into `html-copy` and verified commit history with `git log --oneline`.

## Submission
- **Terminal Output:** [terminal-output.txt](terminal-output.txt)
- **Cloned Repository Code:** [html-copy/index.html](html-copy/index.html)
