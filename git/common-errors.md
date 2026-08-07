# Common Git Errors and Their Fixes

This guide covers some of the most common Git errors beginners face and how to fix them.

---

# 1. Cannot use import statement outside a module

### Error

```text
SyntaxError: Cannot use import statement outside a module
```

### Cause

Node.js is running in CommonJS mode while your project uses ES Modules.

### Fix

```json
{
  "type": "module"
}
```

or use

```js
const packageName = require("package-name");
```

---

# 2. remote origin already exists

### Error

```text
fatal: remote origin already exists
```

### Fix

```bash
git remote -v
git remote remove origin
git remote add origin YOUR_REPOSITORY_URL
```

---

# 3. Updates were rejected because the remote contains work

### Error

```text
Updates were rejected because the remote contains work
```

### Fix

```bash
git pull origin main --no-rebase
git push
```

---

# 4. Merge conflict

### Error

```text
CONFLICT (content)
```

### Fix

Open the conflicted file.

Remove

```text
<<<<<<<
=======
>>>>>>>
```

Save.

```bash
git add .
git commit
```

---

# 5. Detached HEAD

### Error

```text
You are in detached HEAD state.
```

### Fix

```bash
git checkout main
```

or

```bash
git switch main
```

---

# 6. Nothing to commit

### Error

```text
nothing to commit, working tree clean
```

### Meaning

Everything is already committed.

Run

```bash
git status
```

to verify.

---

# 7. Permission denied (publickey)

### Error

```text
Permission denied (publickey)
```

### Fix

Generate a new SSH key

```bash
ssh-keygen
```

Add it to GitHub.

---

# 8. Authentication failed

### Error

```text
Authentication failed
```

### Fix

Use a GitHub Personal Access Token instead of a password.

---

# 9. Failed to push some refs

### Error

```text
failed to push some refs
```

### Fix

```bash
git pull origin main
git push
```

---

# 10. Accidentally committed the wrong file

### Fix

```bash
git restore filename
```

or

```bash
git rm --cached filename
```

---

## Useful Commands

```bash
git status
git log --oneline
git branch
git remote -v
git fetch
git pull
git push
git stash
git restore .
git diff
```

---

## References

- https://git-scm.com/docs
- https://docs.github.com/
