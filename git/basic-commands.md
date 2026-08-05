# Git Basic Commands

Git is a distributed version control system used to track changes in code and collaborate with others.

---

# Initialize a Repository

```bash
git init
```

Creates a new Git repository.

---

# Check Status

```bash
git status
```

Shows modified, staged and untracked files.

---

# Configure Username

```bash
git config --global user.name "Your Name"
```

---

# Configure Email

```bash
git config --global user.email "you@example.com"
```

---

# Add Files

Add one file

```bash
git add README.md
```

Add everything

```bash
git add .
```

---

# Commit

```bash
git commit -m "Initial project"
```

Creates a snapshot of your project.

---

# Commit History

```bash
git log
```

Compact version

```bash
git log --oneline
```

---

# Branches

List branches

```bash
git branch
```

Create

```bash
git branch feature/login
```

Switch

```bash
git checkout feature/login
```

Modern method

```bash
git switch feature/login
```

Create and switch

```bash
git checkout -b feature/login
```

---

# Merge

Switch to main

```bash
git checkout main
```

Merge

```bash
git merge feature/login
```

---

# Clone Repository

```bash
git clone https://github.com/user/repository.git
```

---

# Add Remote

```bash
git remote add origin URL
```

Check

```bash
git remote -v
```

---

# Push

First Push

```bash
git push -u origin main
```

Next Pushes

```bash
git push
```

---

# Pull

```bash
git pull
```

---

# Fetch

```bash
git fetch
```

Downloads changes without merging.

---

# Delete Branch

```bash
git branch -d feature/login
```

---

# Rename Branch

```bash
git branch -M main
```

---

# Restore File

```bash
git restore filename
```

---

# Remove Cached File

```bash
git rm --cached filename
```

---

# Useful Commands

```bash
git diff
```

Shows changes.

```bash
git stash
```

Temporarily saves changes.

```bash
git stash pop
```

Restores saved changes.

```bash
git reset --soft HEAD~1
```

Undo last commit while keeping changes.

---

## Learning Resources

- https://git-scm.com/docs
- https://education.github.com/