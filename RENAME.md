# Git Commands to learn and use

Author: Bidyanand Mishra

# defination

Git - Version Control System (tools) which helps to track changes in the code.
GitHub - Website / Repository that allows developers to store and manage code using Git.

# check git version

git --version

# list files

ls

# list hidden files

ls -a

# present woking directory

pwd

# config username and email

git config --global user.name "Name"
git config --global user.email "Email-ID"

# list details

git config --list

# Clone and Status -->

local - laptop/PC
remote - github repisoritory

# Clone: Cloning a repository on our local machine

git clone <!-- link -->

# Status: display the state of the code

git status

change: modified
new file: untracked
add: staged
after add, commit happens (unchanged)

untracked: new files that git does not yet tracked.
modified: changed
staged: file is ready to be commited
unmodified: unchanged

# Add & Commit

add: adds new or changed file in your working directory to the Git staging area.
git add <!-- file name -->
git add . <!-- add all files>

commit: It is record of change
git commit -m "some message"

# Push Command

Transmit local branch commits to the remote repository branch
git push origin main
git push [alias] [branch]

# Init Command

init - used to create a new git repo
git init
git remote add origin <!-- link -->
git remote -v (to verify remote)
git branch (to check branch)
git branch -M main (to rename branch)
git push origin main

# -u is written to specify upstrem. That meanswe will only going to to push on main branch. Now only git push should be written instead of git push origin main

git push -u origin main
git push
