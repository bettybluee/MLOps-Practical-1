# 🗂️ Week 1 – Git

A hands-on introduction to Git and GitHub workflows for reproducible project management.  
This week focused on understanding commits, branches, issues, and collaboration flow.

---

## 📘 Overview

This repository documents my **Week 1 MLOps practical** exercise.  
The goal was to:
- Create and manage GitHub Issues  
- Edit and commit files using VS Code  
- Link commits to Issues automatically (`closes #issue_number`)  
- Practice advanced version control commands (`amend`, `reset`, `revert`, `cherry-pick`)  
- Explore reproducibility in Git-based workflows  

🔗 **Main Repo:** [MLOps-Practical-1](https://github.com/bettybluee/MLOps-Practical-1)

---

## ⚙️ Quick Start

You can reproduce my Week 1 workflow using the following commands:

```bash
# 1️⃣ Clone the repository
git clone https://github.com/bettybluee/MLOps-Practical-1.git
cd MLOps-Practical-1

# 2️⃣ Edit the README file
code README.md

# 3️⃣ Stage, commit, and push changes
git add README.md
git commit -m "Add About Me section (closes #1)"
git push
````

✅ **Expected Output:**

* The commit appears on GitHub.
* Issue `#1` is automatically closed.

---

## 🗂️ Project Structure

```
MLOps-Practical-1/
├── .gitignore         # Ignore unnecessary local files
└── README.md          # Documentation for Week 1 exercises
```

---

## 🧩 Example Artifacts

* [Closed Issue #1](https://github.com/bettybluee/MLOps-Practical-1/issues/1) — auto-closed by commit
* [Git Practice Repo](https://github.com/bettybluee/git-practice-start) — additional experiments
* Commands tested:

  * `git commit --amend`
  * `git reset` / `git revert`
  * `git cherry-pick`
  * `git stash`
  * Conflict resolution in VS Code

---

## 🛠️ Tech Stack

* **Version Control:** Git & GitHub
* **Editor:** VS Code
* **OS Environment:** macOS
* **Languages Used:** Markdown, Bash

---

## 🧠 Key Learnings

* Learned how Git tracks **project history**, not just files
* Understood **branching and commit movement** (e.g., cherry-pick)
* Fixed issue auto-linking by learning that **issue IDs are repo-specific**
* Practiced safe rollback using `reset` vs. `revert`
* Improved understanding of **reproducible collaboration workflows**

---

## 🤖 GenAI Support

Used GenAI (ChatGPT) to:

* Clarify commands (`reset`, `revert`, `cherry-pick`)
* Understand issue auto-closing syntax
* Review error messages before retrying locally

**Risk Control:** Verified all instructions manually before applying — avoided using destructive commands without testing.

---

## 💬 Reflection

This week helped me internalize how **version control is the foundation of reproducibility**.
Initially, I confused repositories when linking commits to issues, but after debugging, I fully understood GitHub’s issue reference logic.
Learning advanced commands through trial and error (and verified AI help) deepened my confidence in using Git responsibly.

Next steps:

* Visualize branch history using `git log --graph`
* Automate repetitive Git steps via Makefile
* Continue using issues for transparent documentation

---

## 👩‍💻 Author

**Betty Kim**  
📚 Tilburg University – MSc Data Science (Pre-master)  
🗓️ Week 1: Git  
🔗 [GitHub Profile](https://github.com/bettybluee)
