# Git Commands to learn and use

Author: Bidyanand Mishra <br/>

</h2>defination</h2>

Git - Version Control System (tools) which helps to track changes in the code. <br/>
GitHub - Website / Repository that allows developers to store and manage code using Git. <br/>

<h2>check git version</h2>

git --version <br/>

<h2>list files</h2>

ls <br/>

<h2>list hidden files</h2>

ls -a <br/>

<h2>present woking directory</h2>

pwd <br/>

<h2>config username and email</h2>

git config --global user.name "Name" <br/>
git config --global user.email "Email-ID" <br/>

<h2>list details</h2>

git config --list <br/>

<h2>Clone and Status --></h2>

local - laptop/PC <br/>
remote - github repisoritory <br/>

<h2>Clone: Cloning a repository on our local machine</h2>

git clone <- link -> <br/>

<h2>Status: display the state of the code</h2>

git status <br/>

<b>change:</b> modified <br/>
<b>new file:</b> untracked <br/>
<b>add:</b> staged <br/>
after add, <b>commit</b> happens (unchanged) <br/>

<b>untracked:</b> new files that git does not yet tracked. <br/>
<b>modified:</b> changed <br/>
<b>staged:</b> file is ready to be commited <br/>
<b>unmodified:</b> unchanged <br/>

<h2>Add & Commit</h2>

add: adds new or changed file in your working directory to the Git staging area. <br/>
git add <- file name -> <br/>
git add . < add all files > <br/>

<h2>Commit </h2>
It is record of change <br/>
git commit -m "some message" <br/>

<h2>Push Command</h2>

Transmit local branch commits to the remote repository branch <br/>
git push origin main <br/>
git push [alias] [branch] <br/>

<h2>Init Command</h2>

init - used to create a new git repo <br/>
git init <br/>
git remote add origin <- link -> <br/>
git remote -v (to verify remote) <br/>
git branch (to check branch) <br/>
git branch -M main (to rename branch) <br/>
git push origin main <br/>

<h2>-u is written to specify upstrem. That meanswe will only going to to push on main branch. Now only git push should be written instead of git push origin main </h2>

git push -u origin main <br/>
git push

<h2>Branch Commands</h2>

git branch (to check branch)
git branch -M main (to rename branch) <br/>
git checkout <-branch name-> (to navigate) <br/>
git checkout -b <-new branch name-> (to create new branch) <br/>
git branch -d <-branch name-> (to delete branch) <br/>

<h2>Merging Code</h2>
<h3>way 1</h3>
git diff <-branch name-> (to compare commits, branches, files & more) <br/>
git merge <-branch name-> (to merge 2 branches) <br/>

<h3>way 2</h3>
create a PR (Pull Request - It lets you tell others about changes you have pushed to a branch in a repository on GitHub)

<h2>Pull Command</h2>
used to fetch and download content from a remote repo and immediately update the local repo to match that content. <br/>
git pull origin main

<h2>Resolving Merge Conflicts</h2>
An event that take place when Git is usable to immediately resolve differences in code between two commits.

<h2>Undoing Changes</h2>
<h3>Case 1:</h3> staged changes <br/>
git reset <-file name-> <br/>
git reset <br/>

<h3>Case 2:</h3> Commited changes (for 1 commit)
git reset HEAD~1 <br/>

<h3>Case 3:</h3> commited changes (for many commits) <br/>
git reset <-commit hash-> <br/>
git reset --hard <-commit hash-> <br/>

<h2>Fork</h2>
a fork is a new repository that shares code and visibility settings with the original "upstream" repository. <br/>
Fork is a rough copy. <br/>

<h2>Get  log file of commit</h2>
git log
