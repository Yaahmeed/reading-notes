# Class 3 Notes

## Revisions and the Cloud / GIT

GIT is a Distributed Version Control System that stores data in a file made up of snapshots (changes).

A Save is called a Commit
A Commit is equal to a Save As
Git primarily resides on a local disk.

Every change applied to any file or directory is tracked by Git.

## Git states

* Committed (Data securly stored in a local database)
* Modified (File has been changed, but not yet commited to the database)
* Staged (File has been changed and flagged to be committteed in the next snapshot)

## Commit Snapshop

* Head = Most recent version/You are here
* Add messages to commits (captions for snapshot. Why did you make the changes you made.)

## Git vs Github

* Github is NOT Git
* Gitgub is a way to share code with others
* Online place to store code
* It uses Git to help manage team work
* Git (version control) and Github (online code storage)
* Have lots of team members work together on the same files without messing eachother up
* keep a history of each file over time
* Work on code on your own computer and sync it with whats online

## Repositories

* A repository is a collection of files that youve told Git to pay attention to
* *sually, one project = one repository
* Really large projects might have multiple repositories for different parts of their system (ie: front end vs back end)
* Repositories can live on Github and on your computer

## A.C.P. and Gitflow

* A.C.P. - Add, Commit, Push
* ~git status (nothing has changed)
* Stage files (look for "Modified")
* git add < file > to update what will be commited
* git restore < file > to discard changes
* git commit -m "your message"
* git locate (your computer)
* git remote (cloud)
* git push origin main (pushes to Github/cloud)
* git add . (stage all changes for commit)

## Pull changes from Github

* git pull origin main (pull changes from Github)
* Typically MERGE (at this stage)
* git config pull.rebase false
* git pull origin main (PULL CHANGES FROM GITHUB)
* In VS Editor, choose what to keep from merge!

## Import Existing Project

* Move to project target directory (CodeFellows/projects/courses/102)
* git init (creates new subdirectory named .git that has the repository files. No tracking yet)

## Tracking files

* Use the following commands in the terminal:
* git add *.c
* git add LICENSE
* git commit -m " type message here "

## Clone Repository

* To clone Git repository from a particular server use:
* git clone 'https://github.com/test'
* This copies all versions of all files for a project. This command creates a directory called "test" with an initialized .git directory inside of it, which contains all versions of all files for the specified project.
* To clone repository into a directory with another name of your choosing, use:
* git clone 'https://github.com/test' mydirectory
* Now the target repository is in a directory named "mydirectory"

## Steps to push Git changes from terminal

* git status
* git add .
* git commit -m "your message"
* git push origin main
* git status
