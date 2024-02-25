# GIT Project

What is git? Git is a distributed version control system, which essentially solves the problem of sharing source code efficiently and keeping track of changes made to the source code

# Initializing a repository and making commit

## - Initializing a Git repository

  - The steps below are followed;

  1.  Install Git
  2.  Open a Git bash terminal on the computer 
  3.  creare a directory call Devops using;   $mkdir DeVops
  4.  Change into this working directory using; $cd DeVops
  5.  run  $git init command

      ![Alt text](images/gitInit.PNG)


## Making the First Commit

  1.  Inside the working directory, create a file index.txt
  2.  Write a text inside the file say, "GIT learning i quite interesting"
  3.  Add the changes to GIT staging area using; $git add .
  4.  Commit the changes to GIT by running the command; $git commit -m "initial commit", where -m is
      used to provide the commit message.

      ![Alt text](images/gitcommit.PNG)

## Working with branches

Git Branch: This is used to develop a new feature of the application. The changes made in the branch is independent on what is available in the main copy.

    ### Make a new branch by running the command, 
    $git checkout -b newBranch

    ### To list the branch, run the command below;
    $git branch

        ![Alt text](images/gitnewbranch_listing.PNG)

    ### To switch back to the old, use the command, 
    $git checkout main



