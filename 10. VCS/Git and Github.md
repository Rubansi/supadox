# 📘 Version Control with Git and GitHub – Documentation

------

## 1. Introduction to Version Control

**What is Version Control?**
 Version Control is a system that records changes to files over time so you can recall specific versions later. It allows individuals and teams to:

- Track the history of changes.
- Revert to previous versions when needed.
- Collaborate without overwriting each other’s work.

**Why Version Control is Important**

- Ensures a history of project changes.
- Allows collaboration among multiple developers.
- Supports branching and experimentation.
- Prevents data loss.

**Types of Version Control Systems**

1. **Local Version Control** – Keeps changes in your local machine (e.g., RCS).
2. **Centralized Version Control** – A single server stores all versions (e.g., SVN, CVS).
3. **Distributed Version Control (DVCS)** – Every user has a full copy of the repository (e.g., Git, Mercurial).

👉 Git is the most popular DVCS today.

------

## 2. Introduction to Git

**What is Git?**
 Git is a free, open-source, distributed version control system created by Linus Torvalds in 2005. It is optimized for speed, flexibility, and collaboration.

**Why Git?**

- Distributed: Every developer has the full history of the project.
- Fast: Operations are local, making them faster.
- Branching: Easy to create, merge, and delete branches.
- Popular: Used in most modern software projects.

**Key Concepts**

- **Repository (Repo):** A project’s folder tracked by Git.
- **Commit:** A snapshot of project changes.
- **Branch:** A parallel line of development.
- **Merge:** Combining changes from different branches.
- **Remote:** A version of the repo hosted online (e.g., GitHub).

## 3. Setting Up Git

**Install Git:**

- Windows: Download from [git-scm.com](https://git-scm.com?utm_source=chatgpt.com).
- Mac: Use Homebrew (`brew install git`).
- Linux: Use package manager (`sudo apt-get install git`).

**Configure Git:**

```
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
git config --global core.editor "code --wait"
```

**Verify Installation:**

```
git --version
```

## 4. Basic Git Workflow

​	a. **Initialize a Repo**

```
git init
```

​	b. **Clone an Existing Repo**

```
git clone https://github.com/user/repo.git
```

​	c. **Check File Status**

```
git status
```

​	d. **Stage Changes**

```
git add filename.txt

git add . # Or add all changes
```

​	e. **Commit Changes**

```
git commit -m "Add new feature"
```

​	g. **View History**

```
git log
```

## 5. Branching and Merging

**Create a Branch**

```
git branch feature-branch
git checkout feature-branch
# Or combined
git checkout -b feature-branch
```

**Merge Branch**

```
git checkout main
git merge feature-branch
```

**Delete Branch**

```
git branch -d feature-branch
```

**Handling Merge Conflicts**

- Conflicts happen when changes overlap.
- Git marks conflicts in files using `<<<<<<<`, `=======`, and `>>>>>>>`.
- Resolve manually, then commit.

## 6. Working with Remotes (GitHub)

**What is GitHub?**
 GitHub is a platform for hosting Git repositories, enabling collaboration, sharing, and version control in the cloud.

**Connect Local Repo to GitHub**

```
git remote add origin https://github.com/user/repo.git
git branch -M main
git push -u origin main
```

**Push Changes**

```
git push origin main
```

**Pull Changes**

```
git pull origin main
```

**Clone from GitHub**

```
git clone https://github.com/user/repo.git
```