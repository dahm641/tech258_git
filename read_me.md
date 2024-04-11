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

# Film rating project

### *possible film ratings are "universal", "pg", "12", "12a", "15", "18"*
`film_rating = "12a"`
### *use an if statement to check for "universal" rating*
`if film_rating == "universal":
    print("all age groups can watch this film")`
### *else check if film rating is "pg"*
`elif film_rating == "pg":
    print("General viewing, but some scenes may be unsuitable for young children.")`
### *else check if film rating is "12" or "12a"*
`elif film_rating == "12" or "12a":
    print("Films classified 12A and video works classified 12 contain material that is not generally suitable for children aged under 12. No one younger than 12 may see a 12A film in a cinema unless accompanied by an adult.")`
### *else check if film rating is "15"*
`elif film_rating == "15":
    print("No one younger than 15 may see a 15 film in a cinema.")`
### *else check if film rating is "18"*
`elif film_rating == "18":
    print("No one younger than 18 may see an 18 film in a cinema.")`
### *otherwise (none of the above) print statement*
`else:
    print("This is not a correct rating, please use universal, pg, 12, 12a, 15, 18")`

# Loops
## What are loops?

- Loops are programming constructs that allow you to repeat a block of code multiple times. They're handy when you need to perform the same operation over and over again.

- There are two main types of loops: ***for loops*** and ***while loops***.

### **For Loop:**
A for loop is used when you know in advance how many times you want to repeat a block of code. It's often used when you need to iterate over a sequence of elements, like a list or array.

### Example of a for loop in Python
    for i in range(5): 
    print("Iteration", i)
This iterates the letter i (by default increments by 1) and then prints it before iterating again

### **While Loop:** 
A while loop is used when you want to repeat a block of code as long as a condition is true. It's useful when you don't know in advance how many times you need to loop, or when the number of iterations depends on some condition.

### Example of a while loop in Python
    num = 0
    while num < 5:
    print("Iteration", num)
    num += 1
- This code states that the variable `num` is equal to 0 and then states that as long as that varibale is below 5 then print the statement and what the value of the variable is. It then increments it by one. It keeps going until the statement is no longer true at which point it exits the loop

- The key difference between for and while loops is that for loops are typically used when you know the number of iterations beforehand, while while loops are used when you're not sure how many times you need to repeat the code.

 - You might choose a while loop over a for loop when you want to keep iterating until a specific condition is met, which might change during the execution of the loop.