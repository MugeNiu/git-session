# git-session
experiment repo for git exercise in class

git checkout paste id
to go back to the current version: git checkout master
git stash:made changes in my file, want to go to the last stable commit, apply git stash 
	takes you back to the last stable commit 
git log:tells you what commits have been made
git commit -am is the same as git commit add . 

An even more powerful tool is to create new branches:
git checkout -b new-feature: check out a new branch, name can't have spaces
switch back and forth anytime by doing git checkout master
	am: add and have a message 
git checkout master
git merge new-feature 
(the plus and minus are numbers of lines modified, added or removed)
git log: tells you all the commits 

Git merge conflict:
if two people worked on the roject and made changes about the same thing together, you get an error when trying to merge. 
<<<<<<<HEAD is what I have 
>>>>>>> id is what my partner changed 
To fix, just delete on of the changes

git commit -am 'fix merge conflict'
git push
This is why it's good to put data files as external files. So one person can work on the file and another person can work on the JS. 
