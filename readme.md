# Learning Git and GitHub

This repository is dedicated to learning the fundamentals of Git and GitHub. It contains basic concepts, commands, and exercises to help you get comfortable with version control and collaborating on GitHub.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Basic Git Commands](#basic-git-commands)
- [Working with GitHub](#working-with-github)
- [Branching and Merging](#branching-and-merging)
- [Contributing](#contributing)
- [Resources](#resources)

## Introduction
Git is a powerful version control system that helps track changes in files and enables collaboration among multiple developers. GitHub is a cloud-based platform that uses Git for version control and offers additional features for collaboration, such as pull requests and issue tracking.

## Installation
To begin using Git, you'll need to install Git on your machine.

### Install Git:
- [Download Git](https://git-scm.com/downloads) for your operating system.
- Verify the installation by running:
  ```bash
  git --version

### Set Up Git:

After installing, configure your Git identity:

git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

### Basic Git Commands

Here are a few essential Git commands to get started:

    git init: Initialize a new Git repository.
    git clone <repository-url>: Clone an existing repository.
    git status: Check the status of your working directory.
    git add <file>: Stage a file for commit.
    git commit -m "message": Commit changes with a message.
    git push: Push your changes to a remote repository.
    git pull: Pull the latest changes from a remote repository.

### Working with GitHub

    Create a repository:
        Go to your GitHub account and create a new repository.
        Clone the repository using:

    git clone git@github.com:your-username/repo-name.git

### Push your code:

    Add your files, commit your changes, and push them to the GitHub repository.
    Example:

    git add .
    git commit -m "Initial commit"
    git push origin main

### Collaborate using branches and pull requests:

    Create a new branch:

        git checkout -b new-feature

        Push your branch and open a pull request on GitHub.

### Branching and Merging

Branches in Git allow you to work on different features or fixes separately. Once completed, you can merge the changes back into the main branch.
Create a New Branch:



git checkout -b feature-branch

### Merge a Branch:

    Switch to the main branch:


git checkout main

### Merge the feature branch:

    git merge feature-branch

### Contributing

If you'd like to contribute, feel free to:

    Fork the repository.
    Create a new branch.
    Open a pull request with your changes.

### Resources

Here are some resources for further learning:

    Git Documentation
    GitHub Guides
    Pro Git Book




