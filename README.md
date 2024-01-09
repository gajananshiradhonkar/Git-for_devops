# An Introduction to Git: The Basics Every Beginning Developer Should Know.............
As a developer, you'll need to work with a version control system, especially if you're working on a project with other developers. 
A version control system stores the project history so we can easily see what code changes have been implemented, when and by whom. 
If there are issues, a version control system allows you to revert to an earlier code version.

**#The Git Workflow..........**

Git is a distributed version control system. Unlike a centralized version control system, where the project is stored on a central server, each team member using Git has a copy of the project with its history stored on their local machine.
The Git Repository stores all the Project Code. 
The Git Repository is a database that contains all the project code and the history of all code updates. 
The Git repository can be stored on your local machine if you are working on a solo project. 
However, project code is typically stored in a repository on a remote server.


A Basic Git Workflow.................
You start your git project by creating a git repository to track your files or copying a remote repository onto your local drive.
Once you have a local repository on your drive, you check out the project to a new or existing project branch. 
This creates a copy of the project files and directories in your working directory, which you can then update with your changes.
You copy the updated files to the staging area when you've completed your changes. 
The staging area (also called the index) allows you to review your changes before you commit your updates to your local repository.
After you've verified your code in the staging area, you're ready to commit it to the Git repository on your local machine.
You can then push your code to the remote repository.

Git Branches
Any time you make a change to working code, you introduce the possibility of introducing errors to the software project. 
Git Branches help mitigate this possibility by allowing you to keep code changes separate from the main working code.

Using Git branches provides several advantages:

Multiple developers can work on different features simultaneously without affecting the work of other team members.
As a developer, you can ensure that any new features or bug fixes are working correctly before merging your updates into the main code.
If you are working on multiple features, you can create a separate branch for each feature.

The Basic Git Commands Beginning Developers Need to Know...........
1. git init
Git init creates an empty git repository for project tracking.
Once the repository is created, any files added to the repository are automatically tracked.
ex :
git init gaju@gaju-thinkpad:~/Desktop/git_demo$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint: 	git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint: 	git branch -m <name>
Initialized empty Git repository in /home/gaju/Desktop/git_demo/.git/


