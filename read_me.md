# Git learning
## What is version control?
- Version control is like a time machine for your files. It's a system that keeps track of changes you make to your documents, code, or any digital content over time. It allows you to go back to earlier versions if something goes wrong or if you want to see how things evolved. Think of it as a way to save and manage different snapshots of your work as it progresses.

## What is git and how does it work?
Git is a popular version control system used by developers to track changes in their code projects. It works by creating a repository, which is like a folder that holds all the files related to a project, and it keeps track of every change made to those files over time.

Here's how it works in basic terms:

- Initializing a Repository: You start by creating a Git repository in your project folder. This tells Git to start tracking changes in that folder.

- Adding Files: You add files to the repository by telling Git to start tracking them.

- Making Changes: As you work on your project, you make changes to the files in your repository.

- Committing Changes: When you're happy with the changes you've made, you "commit" them to the repository. This is like taking a snapshot of the current state of your project.

- Viewing History: You can view the history of your project and see all the changes that have been made over time.

- Branching and Merging: Git allows you to create branches, which are like separate timelines for your project. You can work on new features or fixes in a branch without affecting the main project. When you're done, you can merge your changes back into the main project.

## basic git commands
### `git innit`
Initializes a new Git repository in the current directory, setting up the necessary files and data structures needed for version control.

### `git status`
Initializes a new Git repository in the current directory, setting up the necessary files and data structures needed for version control.

### `git add`
Adds files to the staging area, preparing them to be included in the next commit.

### `git commit`
Records the changes in the staging area to the repository's history, creating a new commit with a message describing the changes.

### `git log`
Displays a chronological list of commits in the repository, showing information such as the commit hash, author, date, and commit message. It provides a history of changes made to the project.

### `git diff`
Shows the differences between different versions of files in the repository. It highlights the changes made between the working directory and the staging area or between different commits.

### What is `git ignore` and why should we use it?
 `.gitignore` is a file we create to specify which files and folders that Git should ignore. We do this to keep the repository clean and uncluttered and it allows us to use `git add .` which means add all he files to the commit so we dont have to enter them manually due to us having to ignore some files we dont want in our git repo (saves time). 
