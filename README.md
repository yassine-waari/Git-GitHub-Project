Create a folder called learn_git.
`mkdir learn_git`
Cd (change directory) into the learn_git folder.
`cd learn_git`
Create a file called third.txt.
`touch third.txt`
Initialize an empty git repository.
`git init`
Add third.txt to the staging area.
`git add third.txt`
Commit with the message "adding third.txt".
`git commit -m "adding third.txt"`
Check out your commit with git log.
`git log`
Create another file called fourth.txt.
`touch fourth.txt`
Add fourth.txt to the staging area.
`git add .`
Commit with the message "adding fourth.txt"
`git commit -m "adding fourth.txt"`
Remove the third.txt file.
`git rm fourth.txt`
Add this change to the staging area. (Using the command "git add . "
`git add .`;
Commit with the message "removing third.txt".
`git commit -m "removing third.txt"`
Check out your commits using git log.
`git log`
Change your global settings to core.pager=cat - you can read more about that here.
`git config --global core.pager cat`
Write the appropriate command to list all the global configurations for git on your machine.
`git config --global --list`
You can type git config --global to find out how to do this.
`config --global`

