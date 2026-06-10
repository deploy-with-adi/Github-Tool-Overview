# Github-Tool-Overview

This repository contains my Git learning notes and hands-on practice performed on an AWS EC2 instance.

---

## Repository Structure

```text
Github-Tool-Overview/
│
├── README.md
├── git-basics.txt
└── git-commands.txt
```

---

## Git Workflow

```text
Working Directory
       ↓
Staging Area (Index)
       ↓
Local Repository
       ↓
Remote Repository (GitHub)
```

### Workflow Explanation

| Stage             | Purpose                 |
| ----------------- | ----------------------- |
| Working Directory | Create or modify files  |
| Staging Area      | Select files for commit |
| Local Repository  | Store commits locally   |
| Remote Repository | Store code on GitHub    |

---

## Topics Covered

### Git Basics

This file covers:

* Introduction to Git
* Distributed Version Control System (DVCS)
* Git Workflow
* Working Directory
* Staging Area
* Local Repository
* Remote Repository
* Basic Git Concepts

📄 File: `git-basics.txt`

---

### Git Commands

This file covers:

#### Repository Commands

```bash
git init
git status
git add .
git commit -m "message"
```

#### Branch Commands

```bash
git branch
git branch -M main
git checkout -b feature1
```

#### Remote Repository Commands

```bash
git remote add origin <repository-url>
git remote -v
```

#### Push & Pull Commands

```bash
git push
git push -u origin main
git pull
```

#### Clone Commands

```bash
git clone <repository-url>
```

📄 File: `git-commands.txt`

---

## Files

### Git Basics Notes

[git-basics.txt](./git-basics.txt)

Contains detailed explanations of:

* What is Git
* Git Workflow
* Staging Area
* Local Repository
* Remote Repository

---

### Git Commands Reference

[git-commands.txt](./git-commands.txt)

Contains detailed explanations of:

* Repository Commands
* Staging Commands
* Commit Commands
* Branch Commands
* Remote Commands
* Push/Pull Commands
* Clone Commands
* Undo Commands

---

## Commands Practiced

```bash
mkdir B8
cd B8

git init

touch git-basics.txt
touch git-commands.txt

git add .
git commit -m "Initial Commit"

git branch -M main

git remote add origin <repository-url>

git push -u origin main
```

---

## Learning Goal

This repository is part of my DevOps learning journey where I document Git, GitHub, Linux, AWS, and other DevOps concepts with practical examples.

