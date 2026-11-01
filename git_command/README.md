<div align="center">

# 🚀 Git & GitHub Commands

### 📚 Complete Beginner's Notes

<img src="https://img.shields.io/badge/Git-Version_Control-orange?logo=git" />
<img src="https://img.shields.io/badge/GitHub-Repository-black?logo=github" />
<img src="https://img.shields.io/badge/Level-Beginner-green" />

</div>

---

## 🔷 What is Git?

**Git:** A free and open-source distributed version control system used to track changes in source code.

## 🔷 What is GitHub?

**GitHub:** An online platform where developers host repositories, manage projects, and collaborate with others.

---

## 🟢 1. Configuring Git

| Command                                           | Description                |
| ------------------------------------------------- | -------------------------- |
| `git config --global user.name "Uday"`            | Set your Git username.     |
| `git config --global user.email "uday@gmail.com"` | Set your Git email.        |
| `git config --list`                               | Display Git configuration. |

## 🔵 2. Cloning

**Cloning:** Creating a local copy of an existing remote repository.

```bash
git clone repository_url
```

## 🟡 3. Status

**Status:** Displays the current status of files in the working directory and staging area.

```bash
git status
```

## 🟠 4. Add

**Add:** Adds new or modified files from the working directory to the staging area.

```bash
git add filename
```

*Add a particular file.*

```bash
git add .
```

*Add all new and modified files.*

## 🟣 5. Commit

**Commit:** Records staged changes in the local repository.

```bash
git commit -m "your message"
```

## 🔴 6. Push

**Push:** Uploads local repository commits to a remote repository.

```bash
git push origin main
```

Or use:

```bash
git push -u origin main
```

After setting the upstream branch, you can simply use:

```bash
git push
```

## 🟤 7. Pull

**Pull:** Downloads changes from a remote repository and integrates them into the current local branch.

```bash
git pull origin main
```

---

## 🟢 8. Init

**Init:** Initializes a new Git repository in the current directory.

```bash
git init
```

**Connect local repository to GitHub:**

```bash
git remote add origin repository_url
```

**Verify remote repository:**

```bash
git remote -v
```

---

## 🔵 9. Branch Commands

| Command                      | Description                        |
| ---------------------------- | ---------------------------------- |
| `git branch`                 | Display available local branches.  |
| `git branch -m main`         | Rename the current branch to main. |
| `git checkout branchname`    | Switch to another branch.          |
| `git checkout -b branchname` | Create and switch to a new branch. |
| `git branch -d branchname`   | Delete a merged branch.            |

---

## 🟡 10. Merge and Difference

**Diff:** Used to compare changes between commits, branches, and files.

```bash
git diff branchname
```

**Merge:** Combines changes from another branch into the current branch.

```bash
git merge branchname
```

## 🟠 11. Merge Conflicts

**Merge Conflict:** An event that occurs when Git cannot automatically resolve differences between two branches.

**Steps to resolve merge conflicts:**

1. Open the conflicting file.
2. Resolve the conflicting code manually.
3. Add the resolved files.
4. Commit the changes.
5. Push the changes to GitHub.

```bash
git add .
git commit -m "Resolved merge conflicts"
git push origin main
```

---

## 🟣 12. Show All Commits

**Log:** Displays the commit history of the repository.

```bash
git log
```

**Show commits in one line:**

```bash
git log --oneline
```

---

## 🔴 13. Fixing Mistakes

### Case 1: Staged Changes (`git add .`)

Remove all staged changes:

```bash
git reset
```

Remove a particular file from staging:

```bash
git reset filename
```

### Case 2: Committed Changes (`git commit`)

Undo the latest commit:

```bash
git reset HEAD~1
```

Reset to a specific commit:

```bash
git reset commit_hash
```

Reset and discard changes permanently:

```bash
git reset --hard commit_hash
```

⚠️ **Warning:** `git reset --hard` can permanently delete uncommitted changes.

---

## 🟤 14. Forking

**Forking:** Creating your own copy of another developer's repository under your GitHub account.

A fork allows you to modify someone else's project without changing the original repository.

---

<div align="center">

### 👨‍💻 Author

**Uday Kumar**

[GitHub](https://github.com/udaybscitstudent) • [Portfolio](https://udaybscitstudent.github.io/myinfo/)

⭐ If you find these notes helpful, don't forget to give this repository a star!

</div>
