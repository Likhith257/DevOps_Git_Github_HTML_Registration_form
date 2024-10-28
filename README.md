# Git Setup and Repository Cloning Guide

## Overview
This guide provides step-by-step instructions for setting up Git on your local machine and cloning a GitHub repository. Git is a version control system that helps track changes in your code, and GitHub is a platform to host and share repositories.

## Prerequisites
- A GitHub account ([Sign up here](https://github.com/))
- Basic knowledge of command line (for running commands)

## 1. Install Git
To get started, you need to install Git on your machine.

### Windows
1. Download the Git installer from [Git for Windows](https://git-scm.com/download/win).
2. Run the installer and follow the on-screen instructions. Make sure to select the option to add Git to your system’s PATH.
3.  Once installed, open a new Command Prompt or PowerShell window to verify the installation by running `git --version`

### Linux
1. Open your terminal and run `sudo apt-get update` to update the package list.
2. Run `sudo apt-get install git` to install Git.
3. Verify the installation by running `git --version`.

## 2. Configure Git
```
git config --global user.name "Your GitHub Username"
git config --global user.email "your-email@example.com"
```
Replace `"Your GitHub Username"` and `"your-email@example.com"` with your actual GitHub username and email

## 3. Cloning GitHub Repository

1. Now that Git is set up, you can clone a GitHub repository.

2. On GitHub, navigate to the repository you want to clone.

3. Click on the green Code button, and copy the repository’s URL (choose HTTPS or SSH based on your setup).

4. In your terminal, navigate to the directory where you want to clone the repository

```
cd path/to/your/directory
```

5. Cloning the Repo

```
git clone <repository-url>
```

6. Navigate to the Repo

```
cd repository-name
```

## 4. Basic Git Commands

1. Check Repo Status

```
git status
```

2. Stage Changes

```
git add <file-name>
```

3.  Commit Changes

```
git commit -m "commit message"
```

4.  Push Changes to GitHub

```
git push -u origin <branch-name>
```

## Conclusion

By following these steps, you can set up Git, clone repositories from GitHub, and start collaborating on projects. For further details, refer to Git Documentation.