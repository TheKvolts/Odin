set local default git branch by running:

git config --global init.defaultBranch main

Look at this website: https://www.theodinproject.com/lessons/foundations-git-basics


go to your folder using cd
ex. cd Desktop/TheOdinProject

Clone your project using GitHub repository SSH link.

ex. git clone git@github.com:TheKvolts/TheOdinProject.git
Type in terminal 

cd ~/Desktop
git clone git@github.com:TheKvolts/TheOdinProject.git

^Take that link from github repository. 


mkdir: makes file
cd: directs to file
touch: edits file. 

IMPORTANT:
0) git remote -v : to access connection to GitHub to the repository. 
1) 
git status : displays info about staging area. 
Once a file is modified in vscode, git will know. Send modified files to the staging area. 

2) 
Use "git add ." to add all modified files to the staging area.

3) use ' git commit -m "updated the files" '  to commit files. Needs a comment. (use git status) to view later.)

4) use ' git push ' to send all files to GitHub.

Summary
git status
git log

git remote -v
git add .
git commit -m "updated files"
git push (or git push origin main)
