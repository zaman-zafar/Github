# First commands for Git-bash
Git config  --global user.name " your name" 
Git config  --global user.email "your email" 

## To see the file that shows user name and email ID
Cat ~/.gitconfig           
      
## To Create SSH Key
ssh-keygen -o 

## Copy SSH Key and paste inside Github Profile
Cat *location of ssh key*

## To Clone a repository
Git clone *paste the url of repository you want to copy *

## To List all file including hidden files
Ls – la    

 ## lists the files and folders
Dir

## To change the active folder
CD "then folder name” 

## To see the active folder
PWD

## To see the log of activities
Git log

## To create new folder
Mkdir  foldername

## Add heading to Markdown file
Echo "# heading " >> readme. Md

## creates a new Git repository
Git init

## To Stage a file for committing
## Git add readme. Md
Git add .     To add all files 

## To check the status
Git status

## To commit 
Git commit - m "first commit" 

## To rename a branch or create new branch
Git branch - M main 

## To add remote origin
Git remote add origin "link of github repo " 
To see the name of current remote repository
Git remote – v

## To push a commit to a branch
Git push - u origin master 

## To open Vim and create new file
Vim first - push. Txt

## To change repository  use 
Git remote set-url origin "git@github.com:zaman-zafar/sql.git" 

## To clean the screen
Clear      

## To undelete the file
Git checkout - - file name

## To see all branchs
Git branch    to see all branches 

## To create new branch. 
Git checkout - b newbranch 

## To change a branch
Git checkout master     to change branch 

## To remove a file
rm filename. Txt

## To unstage a file after committing
Git reset Head  filename

## To open git GUI
Git merge tool or git gui
