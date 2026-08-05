# Contributing to Student Developer Toolkit

Thank you for your interest in contributing.

This repository is designed to help students and beginner developers learn programming, Git, deployment, interview preparation, and other practical computer science skills.

Contributions should be clear, useful, beginner-friendly, and easy to understand.

---

## Ways to Contribute

You can contribute by:

- Adding programming examples
- Writing tutorials
- Improving existing explanations
- Fixing spelling or grammar mistakes
- Correcting broken code
- Adding interview questions
- Adding Git or deployment guides
- Adding useful learning resources
- Improving the README
- Creating beginner-friendly projects

---

## Before You Start

Before making changes:

1. Check the existing files.
2. Make sure your topic has not already been covered.
3. Search the open issues.
4. Open an issue for major changes before starting.
5. Keep your contribution focused on one topic.

---

## Contribution Steps

### 1. Fork the repository

Click the **Fork** button on GitHub.

### 2. Clone your fork

```bash
git clone https://github.com/YOUR-USERNAME/student-dev-toolkit.git
```

### 3. Enter the project folder

```bash
cd student-dev-toolkit
```

### 4. Create a new branch

Use a clear branch name:

```bash
git checkout -b docs/git-commands
```

Other examples:

```bash
git checkout -b feature/python-api-example
git checkout -b fix/javascript-array-example
git checkout -b docs/vercel-deployment-guide
```

### 5. Make your changes

Add or improve content in the correct folder.

Example:

```text
javascript/promises.js
python/api-request.py
dsa/sorting/bubble-sort.js
deployment/render.md
```

### 6. Test your work

Before committing:

- Run the code.
- Check for syntax errors.
- Confirm the explanation is accurate.
- Check spelling and formatting.
- Make sure links work.

### 7. Stage your changes

```bash
git add .
```

### 8. Commit your changes

Use a clear commit message:

```bash
git commit -m "docs: add JavaScript promises guide"
```

Examples:

```bash
git commit -m "feat: add Python API request example"
git commit -m "fix: correct bubble sort implementation"
git commit -m "docs: improve Vercel deployment instructions"
git commit -m "chore: organize learning resources"
```

### 9. Push your branch

```bash
git push origin your-branch-name
```

Example:

```bash
git push origin docs/git-commands
```

### 10. Open a pull request

Open your fork on GitHub and create a pull request.

In the pull request description, explain:

- What you added
- Why it is useful
- What files were changed
- How the code was tested

---

## Content Guidelines

Please follow these rules:

- Keep explanations beginner-friendly.
- Use simple and clear language.
- Include working examples.
- Add comments only when useful.
- Avoid unnecessary complexity.
- Do not copy content without permission.
- Do not add copyrighted course material.
- Do not add harmful or unsafe code.
- Do not include personal information.
- Do not add generated filler content.
- Make sure code is properly formatted.

---

## File Naming

Use lowercase names with hyphens.

Good examples:

```text
array-methods.js
file-handling.py
git-basic-commands.md
vercel-deployment.md
```

Avoid:

```text
Array Methods.js
newFileFINAL.js
test123.py
```

---

## Markdown Guidelines

Use clear headings:

```md
# Main Title

## Section

### Subsection
```

Use fenced code blocks with a language:

````md
```js
console.log("Hello, world!");
```
