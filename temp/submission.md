# Git Workflow Experience - Laravel Project

## 📌 Overview
This project focused on understanding Git branching, conflict resolution, and collaborative workflows in Laravel.

## 🛠 Steps Followed
1. Created a GitHub repository named `Git-Example`.
2. Cloned the repository locally and configured Git.
3. Created `develop` and feature branches (`feature/user-authentication`, `bugfix/registration-form`).
4. Implemented authentication using Laravel.
5. Fixed registration form issues.
6. Simulated a merge conflict and resolved it manually.
7. Created and merged pull requests into `develop`, then merged `develop` into `main`.

## ⚠️ Challenges Faced
- **Permission Denied** when pushing branches → Resolved by reconfiguring SSH keys.
- **Vite Manifest Not Found** → Fixed by running `npm install && npm run build`.
- **Conflicts in `routes/web.php`** → Manually merged and tested.

## 💡 Lessons Learned
- Use feature branches for better collaboration.
- Always pull the latest changes before pushing.
- Git conflict resolution requires careful review.
- Proper documentation helps in teamwork.

## 🌟 Suggestions for Improvement
- Implement CI/CD pipelines for better automation.
- Use GitHub Actions for automated testing.

---
