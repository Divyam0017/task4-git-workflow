# Task 4 – Git Workflow with Branching and Pull Requests

## 📌 Overview
This task demonstrates a **Git branching workflow** for collaborative development.  
We use separate branches for development work and merge them into the `main` branch using **Pull Requests** on GitHub.

---

## 🛠️ Tools & Technologies
- **Git** – Version control system
- **GitHub** – Remote repository hosting

---

## ⚙️ Steps Followed

1️⃣ **Clone the Repository**
```bash
git clone <https://github.com/Divyam0017/task4-git-workflow.git>
cd task4-git-workflow

2️⃣ Create and Switch to a New Branch (dev)
git checkout -b dev

3️⃣ Make Changes in dev
echo "Task 4 changes" > readme.md
git add readme.md
git commit -m "Updated README for Task 4"

 Push the dev Branch to GitHub
git push -u origin dev

5 Create a Pull Request on GitHub
Go to the repository on GitHub.
Select the dev branch.
Click Compare & Pull Request.
Review changes and click Merge Pull Request to merge into main.

✅ Result
Development branch (dev) successfully merged into the main branch (main) via Pull Request.

Git workflow for branching and merging completed.

Demonstrates collaborative version control best practices.

