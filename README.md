# Git Workflow Assignment

## Project Name
Git Workflow Assignment

## Description
This project is created to practice Git and GitHub operations.
It includes repository setup, branches, commits, merging, merge conflicts,
undo operations, GitHub Issues, Pull Requests, and branch management.

## Folder Structure

Git-Workflow-Assignment/
│
├── src/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── assets/
├── docs/
├── README.md
└── .gitignore

## Git Workflow

1. Create a repository on GitHub.
2. Clone the repository to the local computer.
3. Create and edit project files.
4. Use `git add` to stage changes.
5. Use `git commit` to save changes.
6. Create branches for different features.
7. Merge branches into the develop branch.
8. Merge develop into main.
9. Push changes to GitHub.
10. Use Pull Requests and Issues to manage the project.

## Commands Used

- git clone
- git init
- git status
- git add
- git commit
- git push
- git pull
- git branch
- git checkout
- git switch
- git merge
- git log
- git diff
- git fetch
- git restore
- git reset
- git revert

## Branch Strategy

The project uses the following branches:

- **main** – Final and stable version of the project.
- **develop** – Used to combine and test features.
- **feature/login** – Used for login-related work.
- **feature/navbar** – Used for navbar-related work.
- **feature/footer** – Used for footer-related work.

Feature branches are merged into `develop`, and after testing,
`develop` is merged into `main`.