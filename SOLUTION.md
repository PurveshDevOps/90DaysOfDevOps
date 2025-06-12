** Summarizing the process and the Git commands i used.

cd ..
ls
ssh
sudo apt-get update
sudo apt-get upgrade
git status
mkdir week-4-challenge
cd week-4-challenge/
git init
git status
git branch
touch info.txt
vim info.txt
git add info.txt
git commit -m "Initial commit: Add info.txt with introductory content"
git remote -v
git remote add origin https://github.com/PurveshDevOps/90DaysOfDevOps.git
git push origin master
git remote -v
git remote set-url origin https://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@github.com/PurveshDevOps/90DaysOfDevOps.git
git pull origin master
git push origin master
git pull origin master --rebase
git push origin master
git log
git checkout -b feature-update
vim info.txt
git add info.txt
git commit -m "feature-update: Enhance info.txt with additional details"
git push origin feature-update
git checkout master
git pull origin master
cd week-4-challenge/
ls
git clone git@github.com:PurveshDevOps/90DaysOfDevOps.git
yes
git branch
git checkout feature-update
git clone git@github.com:PurveshDevOps/90DaysOfDevOps.git
clear
git checkout -b experimental
git branch
vim info.txt
git checkout master
git status
git add info.txt
git commit -m "added info.txt"
git push origin master
git status
git checkout feature-update
git merge experimental
git branch
git checkout feature-update
touch solution.md
git pull origin feature-update
git push origin feature-update
git status
git add solution.md
git commit -m "added solution.md to feature-update"
git push origin feature-update
