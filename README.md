# Ascendum Demo Project

This project uses Git for version control. Follow the steps below to clone the repository, work on a feature branch, and safely push your changes to the remote repository.

## 🛠️ Git Workflow

### 1. Clone the repository
```bash
git clone <repository_url>
```

### 2. Navigate into the project directory
```bash
cd ascendum_demo
```

### 3. Checkout your working branch  
Replace `branch_name` with the name of your branch.
```bash
git checkout original_branch_name
```

### 4. Pull the latest changes from the remote branch
```bash
git pull origin original_branch_name
```

### 5. Create and switch to your new feature branch  
Replace `my_branch_name` with your actual branch name.
```bash
git checkout -b your_branch_name
```

#########################################################################


### 6. Stage all changes
```bash
git add .
```

### 7. Check the status of your working directory
```bash
git status
```

### 8. Commit your changes with a meaningful message
```bash
git commit -m "Your commit message here"
```

### 9. Pull the latest changes from the main branch (to avoid conflicts)  
Replace `main_branch_name` with your main development branch, such as `main` or `develop`.
```bash
git pull origin main_branch_name
```

### 10. Push your committed changes to your branch  
Replace `my_branch_name` with your actual branch name.
```bash
git push origin my_branch_name
```

---

## ✅ Best Practices

- Always pull before pushing to avoid conflicts.
- Use clear, descriptive commit messages.
- Don’t push directly to `main` or `develop`; use feature branches.
- Regularly pull from `main` to keep your branch updated.
- compare the push request and add meaningfull comment
- Before commit to github check the branch it should not be main
- eg order_tracking_system <- shivam_change
- Not main <- shivam_change
- Neverever merge the code.
