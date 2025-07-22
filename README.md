
# 🚀 Ascendum Demo Project – Git Workflow Guide

This guide outlines the **standard Git workflow** to help developers contribute efficiently and safely to the project. Always follow these practices to maintain a clean and collaborative development process.

---

## 🛠️ Git Workflow

### 1️⃣ Clone the repository
```bash
git clone <repository_url>
```

### 2️⃣ Navigate into the project directory
```bash
cd ascendum_poc
```

### 3️⃣ Checkout the base branch  
Replace `original_branch_name` with the actual base branch (e.g., `develop` or `main`).
```bash
git checkout original_branch_name
```

### 4️⃣ Pull the latest changes
```bash
git pull origin original_branch_name
```

### 5️⃣ Create and switch to a new feature branch  
Use a meaningful branch name. For example: `order_tracking_shivam`.
```bash
git checkout -b your_branch_name
```

---

## 🧪 Development Workflow

### 6️⃣ Stage your changes
```bash
git add .
```

### 7️⃣ Check the status
```bash
git status
```

### 8️⃣ Commit with a clear message  
Use messages like `"Added API for order tracking"` or `"Fixed UI issue in header"`.
```bash
git commit -m "Your descriptive commit message"
```

### 9️⃣ Pull latest changes from main/development branch to avoid conflicts  
Replace `main_branch_name` with your project's main branch (`main` or `develop`).
```bash
git pull origin main_branch_name
```

### 🔟 Push your feature branch to remote
```bash
git push origin your_branch_name
```

---

## ✅ Git Best Practices

- 🔄 **Always pull before pushing** to avoid merge conflicts.
- 📝 **Write meaningful commit messages** that reflect what was changed.
- 🌿 **Never commit directly to `main` or `develop`.** Always use a feature branch.
- 📥 **Regularly pull from `main`** (or `develop`) to keep your branch up to date.
- 🧪 **Always test your changes** locally before pushing.
- 🔍 **When creating a pull request (PR):**
  - Compare it against the correct base branch (not `main` unless intended).
  - Add a clear title and description explaining your changes.
- 🚫 **Never merge code yourself.** Only reviewers or leads should merge after code review and approval.

---

## 📌 Example Workflow

**✅ Correct:**
```
Branch: order_tracking_system <- shivam_changes
```

**❌ Avoid:**
```
Branch: main <- shivam_changes
```

---

## 👥 Team Collaboration Notes

- Use **Pull Requests (PRs)** for all code contributions.
- **Assign reviewers** and wait for approvals before merging.
- **Document major changes** or decisions in your PR description.

---
