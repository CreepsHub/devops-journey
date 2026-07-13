# Git Cheat Sheet

## Check Git Status

```bash
git status
```

Shows the current state of your project.

---

## View Commit History

```bash
git log
```

Short version:

```bash
git log --oneline
```

---

## Stage All Changes

```bash
git add .
```

Prepare all changed files for the next commit.

---

## Stage One File

```bash
git add filename
```

Example:

```bash
git add README.md
```

---

## Commit Changes

```bash
git commit -m "Your commit message"
```

Example:

```bash
git commit -m "Complete Linux Day 4 Navigation fundamentals"
```

---

## Upload to GitHub

```bash
git push
```

Uploads commits to GitHub.

---

## Download Latest Changes

```bash
git pull
```

Downloads new commits from GitHub.

---

## Clone a Repository

```bash
git clone <repository-url>
```

Example:

```bash
git clone https://github.com/CreepsHub/devops-journey.git
```

---

## Create a Branch

```bash
git branch branch-name
```

Example:

```bash
git branch feature-login
```

---

## Switch Branches

```bash
git checkout branch-name
```

Modern alternative:

```bash
git switch branch-name
```

---

## Create and Switch

```bash
git checkout -b branch-name
```

Modern:

```bash
git switch -c branch-name
```

---

## List Branches

```bash
git branch
```

Current branch has:

```
*
```

---

## Delete a Branch

```bash
git branch -d branch-name
```

---

## Rename a File (Git notices automatically)

```bash
mv oldname.txt newname.txt
git add .
git commit -m "Rename file"
```

---

## See Remote Repository

```bash
git remote -v
```

---

## See Differences

```bash
git diff
```

Shows changes before committing.

---

## Restore File

```bash
git restore filename
```

---

## Common Workflow

```bash
git status
git add .
git commit -m "Meaningful message"
git push
```

---

## Before Starting Work

```bash
git pull
```

---

## Before Finishing Work

```bash
git status
git add .
git commit -m "Describe your work"
git push
```

---

## Check commit date 

git log --pretty=fuller -1

-------------------

## Check EMAIL ADDR.

git config --get user.email

-------------------

# Git Vocabulary

Repository = Project

Commit = Snapshot

Branch = Separate line of development

Merge = Combine branches

Clone = Download repository

Push = Upload commits

Pull = Download latest changes

Remote = GitHub repository

Local = Your computer

Origin = Default remote GitHub repository

HEAD = Current position in Git history