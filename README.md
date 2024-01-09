# An Introduction to Git: The Basics Every Beginning Developer Should Know.............
As a developer, you'll need to work with a version control system, especially if you're working on a project with other developers. 
A version control system stores the project history so we can easily see what code changes have been implemented, when and by whom. 
If there are issues, a version control system allows you to revert to an earlier code version.
Git is a distributed version control system. Unlike a centralized version control system, where the project is stored on a central server, each team member using Git has a copy of the project with its history stored on their local machine.
The Git Repository stores all the Project Code. 
The Git Repository is a database that contains all the project code and the history of all code updates. 
The Git repository can be stored on your local machine if you are working on a solo project. 
However, project code is typically stored in a repository on a remote server.

###################################################################################################################################################
# Uses of Git............
1] Git is used to tracking changes in the source code.
2] Distributed version control tool used for source code management.
3] Allows multiple developers to work together.
4] Supports non-linear development because of its thousands of parallel branches.

###################################################################################################################################################

# Features of Git............
1.Free and open-source
2.Tracks history
3.Supports non-linear development
4.Creates backup
5.Scalable
6.Supports collaboration
7.Branching is easier
8.Distributed development.

###################################################################################################################################################

# The Git Workflow.........
You start your git project by creating a git repository to track your files or copying a remote repository onto your local drive.
Once you have a local repository on your drive, you check out the project to a new or existing project branch. 
This creates a copy of the project files and directories in your working directory, which you can then update with your changes.
You copy the updated files to the staging area when you've completed your changes. 
-----------------------------------------------------------------------------------------------------------------------------------------
# 1] Working directory - 
This is the area where you modify your existing files.
----------------------------------------------------------------------------------------------------------------------------------------
# 2]  Staging area (Index) - 
In this, the files in your working directory are staged and snapshots are added.  
allows you to review your changes before you commit your updates to your local repository.
After you've verified your code in the staging area, you're ready to commit it to the Git repository on your local machine.
You can then push your code to the remote repository.

----------------------------------------------------------------------------------------------------------------------------------------
# 3] Git directory or repository - 
It is basically where you perform all the changes
that need to be made i.e. perform commits to branch, checkout branch, make changes etc.
----------------------------------------------------------------------------------------------------------------------------------------

# =================================================Install Git: Installation in Linux====================================================
# You can install Git on Linux using the command apt-get :
$ sudo apt-get update
$ sudo apt-get install git
# Configure your username and email using the following command:
$ git config --global user.name "user_name"
$ git config --global user.email "user_email@gmail.com"





