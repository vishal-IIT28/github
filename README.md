# Git & GitHub Complete Notes

A beginner-friendly guide to learning **Git and GitHub** with commands, workflow diagrams, and examples.

This repository contains structured notes that help developers understand version control and collaboration using Git.

---

# Table of Contents

1. Git Introduction
2. Git Installation
3. Git Basic Commands
4. Git Workflow
5. Branching
6. Merging
7. Pull Requests
8. Undoing Changes
9. Git Cheat Sheet

---

# What is Git?

Git is a **distributed version control system** used to track changes in source code during software development.

### Key Features

- Version Tracking
- Collaboration
- Branching
- Merging
- Open Source
- Fast and Scalable

---

# What is GitHub?

GitHub is a **platform for hosting Git repositories** and collaborating on projects.

Developers use GitHub to:

- store code
- manage versions
- collaborate with teams
- review code through Pull Requests

---

# Git Workflow
  GitHub Repository
         │
         ▼
       Clone
         │
         ▼
       Modify
         │
         ▼
        Add
         │
         ▼
       Commit
         │
         ▼
        Push


---

# Basic Git Commands

### Check git version
git --version

### Configure Git
git config --global user.name "Your Name"
git config --global user.email "your@email.com"

### Initialize repository
git init

### Clone repository
git clone <repository-url>

### Add files
git add .

### Commit changes
git commit -m "commit message"

### Push to GitHub


git push origin main


---

# Git Branching

Branches allow developers to work on new features without affecting the main code.


main branch
|
|---- feature-1
|
|---- feature-2


### Branch Commands


git branch
git branch new-branch
git checkout new-branch
git checkout -b feature-branch
git branch -d branch-name


---

# Merging Branches


git merge branch-name


Used to combine changes from different branches.

---

# Pull Requests

A **Pull Request (PR)** allows developers to propose changes and merge them after review.

Steps:

1. Create new branch
2. Push branch to GitHub
3. Create Pull Request
4. Review changes
5. Merge code

---

# Undoing Changes

### Unstage file


git reset filename


### Undo last commit


git reset HEAD~1


### Hard reset


git reset --hard commit-hash


---

# Git Cheat Sheet

| Command | Purpose |
|---|---|
| git status | show file state |
| git add | stage files |
| git commit | save changes |
| git push | upload code |
| git pull | download updates |
| git branch | manage branches |

---

# Repository Structure


git-github-notes
│
├── README.md
├── docs
├── images
└── LICENSE


---

# Contributing

Feel free to fork the repository and improve the notes.

---

# License

open source
