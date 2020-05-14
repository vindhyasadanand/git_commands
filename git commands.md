# Git commands

1. git init

   this command is to turn a directory into an empty git repository  because we need local repository to work with

   what is a local repository repository?

   it is the private copy of whole repository 

   ![](C:\Users\vindhya hegde\Pictures\git init.jpg)

2. git add 

   it add all the files to the staging area for git 

   if we modify some file and now we want to add it to our github repository in order to do that use 

   `git add  filename`     

   if we want to add all file to the staging area then `git add .`   it will add all the files that are present in local repository to the staging area.

   3. git commit

      it records the changes made to the files in the local repository.

      so all the modified files will be present in staging when we do `git commit`  it will record all the changes in the local repository.

      `git commit -m "commit message"`

      4. git status

         it will return the current state of the repository.

         it will return the current branch and it will shows if there is something is present in the staging area but we haven't committed  

         5.git config

           with Git there are many configurations and settings possible.

         using git config command globally

         `git config --global  user.name."username"`

         `git config  --global user.email."email id"`

         if we want to execute this in the current repository

         `git config user.name."username"`

         `git config user.email."email id"`

         5.Branching

            Usually branch is created to work on a new feature. 

            

   