# Code Club: Git Basics

Welcome to Day 1 of Code Club! This repository is for practicing the fundamentals of Git — no code to run, just files to edit.

## Prerequisites

Before you start, you should have:

- [ ] A GitHub account
- [ ] Git installed on your machine
- [ ] A code editor (VS Code recommended)
- [ ] Access to this repository as a collaborator

## Setup

1. **Clone this repository**

   ```bash
   git clone git@github.com:ajcumine/code-club-git-basics.git
   cd code-club-git-basics
   ```

2. **Check your Git configuration**

   ```bash
   git status
   ```

3. **Make sure you are on the main branch**

   ```bash
   git branch
   ```

## Today's Exercises

### Exercise 1: Add Your Own File

1. Create a new branch: `git checkout -b add-<your-name>`
2. Create a new file named `<your-name>.md`
3. Add your name and a fun fact about yourself
4. Stage, commit, and push your changes
5. Open a Pull Request on GitHub

### Exercise 2: Edit the Shared File

1. Pull the latest changes from `main`
2. Create a new branch: `git checkout -b update-team`
3. Edit the `team.md` file to add your name
4. Stage, commit, and push
5. Open a Pull Request — you might encounter a merge conflict!

### Exercise 3: Resolve a Merge Conflict

When instructed, we will resolve a merge conflict together as a group.

## Helpful Commands

| Command | What it does |
|--------|-------------|
| `git status` | See what's changed |
| `git add <file>` | Stage a file |
| `git commit -m "message"` | Commit staged changes |
| `git push origin <branch>` | Push to GitHub |
| `git pull origin main` | Get latest changes |
| `git checkout -b <branch>` | Create and switch to a new branch |
| `git log` | See commit history |
