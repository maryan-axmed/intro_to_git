# Terminal CheatSheet 
This cheatsheet will run through the Git commands used in the terminal.
<br> Git commands: </br>

* **git config --global user.name "first_name last_name"**- set a name to associate with your commits
* **git config --global user.email "email@domain.com"**- set an email to associate with your commits
* **mkdir <directory/folder_name>**- create a new directory folder 
* **touch <file_name.extension>**- create a new file
* **git mv <file_name.extension> <folder_you_want_to_move_to>**- move file to a new folder
* *git rm
* **git init**- set up git repository 
* **git add**- add a file(s) to the staging phase 
  * **git add `.`**- add all files from chosen directory to the staging phase
* **git commit m-"message"**- commit changes, with a message, to the repository
* **git status**- this command does a few things:
  * lists the files you have made changes to
  * lists the files you have modified and have yet to add/commit 
* **git log**- review commits 
* **git remote add origin <url_of_remote/GitHub_repository>**- connect your remote server to your local repository
* **git branch <branch>**- create a git branch with any name 
> NOTE: The default branch name in Git is 'master'. <br> You can view all your branches and change between branches using the 'git branch' and 'git checkout <branchname>', respectively. </br>
* **git push**-push your project from your local repository to your remote repository
* **git pull**- fetch and merge changes made on the local repository to your remote repository 


# Extension: .gitignore
When you are sharing a code, there may be something you will not want to share e.g. persoal files. 
<br> You can specify which files you want to ignore using '.gitignore' and git will not track 
files specified in '.gitignore' </br>

>How to create a '.gitignore' file:
```
• Go to your root directory on Git
• Create a file using the command: "touch .gitignore"
• Open the file using a text editor 
• Add the file name of the files you want to be ignored 
```