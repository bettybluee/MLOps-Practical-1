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
