# GitLesson2
## Ctrl+Future Program Github Fundamentals Training Day 2: Learning Branches
## Prepare your working envoriment
- **mkdir funny** This command creates a directory called "funny"
- **cd funny** This command helps you to get into the directory
- **git init** This command helps you to initialize the repo
- **touch index.html** This command creates an empty html file called "index.html"
- **ls** This command lists the contents of the directory.
- **vim index.html** This command helps you to open a text editor which allows you to edit the html file.
- When the text editor opens, you should press "**i**" on your keyboard to activate the **insert mode**. After you're done with the changes, you should press "**esc**" on your keyboard to exit the insert mode. After exiting from the insert mode, you have to write "**:wq**" to save changes you made and exit from the file.
## Push to remote repo ( GitHub )
- **git status** This command helps you to check the status of the repo before you add the index.html file to the staging area.
- At this point, you are free to add the file to the staging area by these 3 commands:  
  **git add .**  
  **git add --all**  
  **git add index.html**  ( This only adds the specific file.)
- **git commit -m "This is my commit message."** At this point, we have to take a snapshot of the files in the staging area. To do that, have to use the command above. You can write your own commit message inside the double quotes.
- **git push origin master** This command helps you to push the files in the staging area to the repository.
## Check your commit history  
- **git log** This command helps you to see your commit history.  
## Checking the changes on the GitHub  
- Visit your repo link on GitHub to check the changes you made.
## Creating another branch and merging it with the Master branch  
- **git branch newbranch** This command helps you to create a new branch called "newbranch".
- **git branch** This command lists the branches that you made so far.
- **git checkout newbranch** This command helps you to switch to the new branch you created.
## Push the new branch to the repo  
- The original push command goes like this: "**git push origin "name of the branch"**
  What we have to do here is that to put the name of the new branch inside the double quotes.
  **git push origin newbranch** This command helps you to push the new branch to the repo.
-Ignore any files with the .log extension  
-Ignore everything in any directory named temp  
