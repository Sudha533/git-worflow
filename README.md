# git-workflow
Git is a version control system that allows multiple people to work on a project simultaneously, track changes over time, and collaborate efficiently. It is particularly popular in software development but can be used for any project that involves file changes.

## Key Concepts
**Repository:**

1. A repository is like a project's folder. It contains all the project files and the entire history of their changes.
2. You can create a local repository on your computer and also have a remote repository on platforms like GitHub, GitLab, or Bitbucket.

**Commit:**

1. A commit is like a snapshot of your repository at a specific point in time. Each commit has a unique ID and a message describing the changes.
2. You make a commit when you've made changes to your files that you want to save.

**Branch:**

1. A branch is a separate line of development. The default branch in most repositories is called main (formerly master).
2. Branches allow you to work on different features or fixes simultaneously without affecting the main codebase.

**Merge:**

1. Merging is the process of combining changes from one branch into another. This is typically done when a feature is complete and ready to be integrated into the main branch.
   
**Clone:**
1. Cloning a repository means creating a copy of a remote repository on your local machine.
   
**Pull:**
1. Pulling means fetching changes from a remote repository and merging them into your local repository.
   
**Push:**
1. Pushing means sending your commits from your local repository to a remote repository.

## Basic Git Workflow

**Install Git:**
Download and install Git
**Configure Git:**
```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
**Create a New Repository:**
```
mkdir my-project
cd my-project
git init
```
**Clone an Existing Repository:**
```
git clone https://github.com/username/repository.git
```
**Check the Status of Your Repo:**
```
git status
```
**Add Files to Staging Area:**
```
git add filename
# Or to add all changes
git add .
```
**Commit Your Changes:**
```
git commit -m "Commit message describing your changes"
```
**Push Changes to a Remote Repository:**
```
git push origin branch-name
```
**Pull Changes from a Remote Repository:**
```
git pull origin main
```
**Create a New Branch:**
```
git branch new-branch-name
git checkout new-branch-name
# Or create and switch to the new branch in one command
git checkout -b new-branch-name
```
**Merge a Branch into Another:**
```
# Switch to the branch you want to merge into
git checkout main
# Merge the other branch
git merge new-branch-name
```


