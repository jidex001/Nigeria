# Nigeria

IDEs: 
Types of IDE; git bash, Linux command line, Virtual Studio, Virtual Studio Code, JetBrains
Command to clone:
•	git clone <repoURL>
Set up global config:
git config --global user.name "sunday"
git config --global user.email "sunday_ebosele@yahoo.com"

To check your current branch:
•	[root@test iphone10]# git branch
To create a new branch:
•	[root@test iphone10]# git checkout -b Sunday
To know the status of your git repository:
•	[root@test iphone10]# git status
To add the file to a repo:
•	[root@test iphone10]# git add .
TO commit a file:
•	[root@test iphone10]# git commit -m <commit message>
To push to central or upstream repo:
•	[root@test iphone10]# git push origin <BranchName>

Merge Request:
For you to be able to merge a branch to a master branch, you need to create a Merge Request or Pull Request.

echo "# Olatest" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/jidex002/Olatest.git
git push -u origin main

…or push an existing repository from the command line

git remote add origin https://github.com/jidex002/Olatest.git
git branch -M main
git push -u origin main



•

