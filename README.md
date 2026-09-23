# A02 - Git, GitHub, and VS Code Tutorial

## Introduction

This tutorial explains how to use Git, GitHub, and Visual Studio Code (VS Code) to create and manage a project. Git is used to track changes made to files, while GitHub allows repositories to be stored and shared online. VS Code is an editor that can be used to create and edit project files.

## Part 1: Setting Up Git, GitHub, and VS Code

### Step 1: Create a GitHub Account

1. Go to https://github.com/
2. Click "Sign up."
3. Enter your email address and create a password.
4. Choose a username.
5. Complete the verification process.
6. Sign in to your new GitHub account.

### Step 2: Install Git

1. Go to https://git-scm.com/downloads
2. Select the download for your operating system.
3. Download and run the installer.
4. Follow the installation instructions.
5. After installation, Git can be used through a terminal or through an editor such as VS Code.

### Step 3: Install Visual Studio Code

1. Go to https://code.visualstudio.com/
2. Download the version for your operating system.
3. Open the downloaded installer.
4. Follow the installation instructions.
5. Open VS Code after installation is complete.

### Step 4: Create a GitHub Repository

1. Sign in to GitHub.
2. Click the "+" button and select "New repository."
3. Enter a name for the repository.
4. Choose whether the repository will be public or private.
5. Select the option to add a README file if needed.
6. Click "Create repository."

### Step 5: Clone a Repository

1. Open the repository on GitHub.
2. Click the green "Code" button.
3. Copy the HTTPS URL.
4. Open VS Code.
5. Open the Command Palette.
6. Select "Git: Clone."
7. Paste the repository URL.
8. Select a location on the computer where the repository will be saved.
9. Open the cloned repository in VS Code.

### Step 6: Edit the Project

1. Open a file in VS Code.
2. Make the necessary changes to the file.
3. Save the changes.
4. Open the Source Control section in VS Code to view the changed files.

### Step 7: Commit Changes

1. Open Source Control in VS Code.
2. Stage the changes that should be included in the commit.
3. Enter a clear commit message describing the changes.
4. Click "Commit."

An example commit message is:

`Feature: added workflow for using GitHub`

### Step 8: Push Changes to GitHub

1. After committing the changes, select "Push" or "Sync Changes" in VS Code.
2. VS Code sends the committed changes to the remote GitHub repository.
3. Open the repository on GitHub to confirm that the changes appear online.

### Step 9: Pull Changes

1. Open the repository in VS Code.
2. Open Source Control.
3. Select "Pull" to retrieve changes from the remote repository.
4. Git will update the local project with the newest changes.

### Step 10: Create and Merge a Branch

1. Create a new branch when working on a separate feature or change.
2. Give the branch a descriptive name.
3. Make and commit changes on the branch.
4. Push the branch to GitHub.
5. The branch can later be merged into the main branch after the changes have been reviewed.

## Part 2: Glossary

- **Branch** - A separate version of a repository that allows changes to be made without immediately changing the main version of the project.

- **Clone** - A local copy of a remote repository that is downloaded to a computer.

- **Commit** - A saved snapshot of changes made to files in a Git repository.

- **Fetch** - A Git command that retrieves updated information and changes from a remote repository without automatically merging them into the local files.

- **GIT** - A distributed version control system used to track changes to files and coordinate work on software projects.

- **Github** - An online platform used to host Git repositories and collaborate on projects.

- **Merge** - The process of combining changes from one branch into another branch.

- **Merge Conflict** - A situation that occurs when Git cannot automatically combine changes because conflicting changes were made to the same part of a file.

- **Push** - The process of sending local commits to a remote repository such as GitHub.

- **Pull** - The process of retrieving changes from a remote repository and integrating them into the local repository.

- **Remote** - A version of a repository stored somewhere else, such as on GitHub, that is connected to the local repository.

- **Repository** - A project location that stores files and tracks their revision history using Git.

## References

- GitHub. "GitHub Docs." https://docs.github.com/
- Git. "Git Documentation." https://git-scm.com/doc
- Microsoft. "Visual Studio Code Documentation." https://code.visualstudio.com/docs
