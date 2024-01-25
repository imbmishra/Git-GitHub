# Git Commands to learn and use

Author: Bidyanand Mishra <br/>

# defination

Git - Version Control System (tools) which helps to track changes in the code. <br/>
GitHub - Website / Repository that allows developers to store and manage code using Git. <br/>

# check git version

git --version <br/>

# list files

ls <br/>

# list hidden files

ls -a <br/>

# present woking directory

pwd <br/>

# config username and email

git config --global user.name "Name" <br/>
git config --global user.email "Email-ID" <br/>

# list details

git config --list <br/>

# Clone and Status -->

local - laptop/PC <br/>
remote - github repisoritory <br/>

# Clone: Cloning a repository on our local machine

git clone <- link -> <br/>

# Status: display the state of the code

git status <br/>

change: modified <br/>
new file: untracked <br/>
add: staged <br/>
after add, commit happens (unchanged) <br/>

untracked: new files that git does not yet tracked. <br/>
modified: changed <br/>
staged: file is ready to be commited <br/>
unmodified: unchanged <br/>

# Add & Commit

add: adds new or changed file in your working directory to the Git staging area. <br/>
git add <- file name -> <br/>
git add . < add all files > <br/>

commit: It is record of change <br/>
git commit -m "some message" <br/>

# Push Command

Transmit local branch commits to the remote repository branch <br/>
git push origin main <br/>
git push [alias] [branch] <br/>

# Init Command

init - used to create a new git repo <br/>
git init <br/>
git remote add origin <- link -> <br/>
git remote -v (to verify remote) <br/>
git branch (to check branch) <br/>
git branch -M main (to rename branch) <br/>
git push origin main <br/>

# -u is written to specify upstrem. That meanswe will only going to to push on main branch. Now only git push should be written instead of git push origin main

git push -u origin main <br/>
git push
