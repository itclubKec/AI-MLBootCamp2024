# AI ML Bootcamp 2024 - Projects Repository

Welcome to the AI/ML Bootcamp 2024 Projects Repository! This repository is dedicated to hosting and tracking the progress of various projects undertaken by participants during the bootcamp. Each project is organized as a subtree within this repository to facilitate easy management and progress tracking.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Rules and Guidelines](#rules-and-guidelines)
  - [Commit Messages](#commit-messages)
- [Getting Started](#getting-started)
  - [Creating a New Project Repository](#creating-a-new-project-repository)
  - [Working on Your Project](#working-on-your-project)
  - [Linking Subtrees](#linking-subtrees)
- [Contact](#contact)

## Overview

This repository is designed to track the progress of various projects developed during the IT Club Bootcamp 2024. Each project is stored as a subtree, which enables participants to work independently while maintaining a clear structure within the main repository.

## Project Structure

The repository is structured as follows:

```
/root
│
├── project1/
│   └── (Project 1 files and directories)
│
├── project2/
│   └── (Project 2 files and directories)
│
└── projectN/
    └── (Project N files and directories)
```

## Rules and Guidelines

### Commit Messages

Commit messages are essential for tracking progress and should follow these guidelines:
Commit messages should be in the format of <type>: <description> where type is one of the following:

    feat: A new feature
    fix: A bug fix
    docs: Documentation only changes
    style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
    refactor: A code change that neither fixes a bug nor adds a feature
    perf: A code change that improves performance
    chore: Changes to the build process or auxiliary tools and libraries such as documentation generation

NOTE: Please try to commit each features in your project for better evaluation. 

### Creating a New Project Repository

Each participant should create their own repository for their project. Follow these steps:

1. **Create Repository**: Create a new repository on GitHub.
2. **Initialize Repository**: Initialize the repository with a `README.md` and any necessary files.

## Getting Started

### Working on Your Project

While working on your project, follow these guidelines to ensure efficient commits and clear progress tracking:

1. **Frequent Commits**: Make frequent commits to document progress.
2. **Descriptive Messages**: Use descriptive commit messages as outlined in the [Commit Messages](#commit-messages) section.

### Linking Subtrees - for Organizers Only

The IT Club Bootcamp organizers will manage linking the subtrees to your project repositories. To link a subtree, the organizers will follow these steps:

1. **Add Subtree**: Add your repository as a subtree in the main repository with the `--squash` flag to ensure a cleaner commit history.
   ```bash
   git subtree add --prefix=projectName --squash https://github.com/user/projectName.git main
   ```
2. **Update Subtree**: To pull updates from your repository, the organizers will use:
   ```bash
   git subtree pull --prefix=projectName --squash https://github.com/user/projectName.git main
   ```

## Contact

For any questions or issues, please contact the IT Club Bootcamp 2024 organizers at https://itclub-web.vercel.app.

---

Thank you for participating in the IT Club Bootcamp 2024! Let's code, collaborate, and create amazing projects together!
