Stage 1: 

mkdir ml-project
cd ml-project
git init
touch train.py predict.py utils.py README.md
git status


Stage 2: 

git add train.py utils.py
git commit -m "Add training script and utilities"
git branch -M main
git remote add origin https://github.com/bharanidharan-ss/ml-project.git
git push -u origin main


Stage 3: 

git pull origin main
git add utils.py config.py
git commit -m "Update utils and add config file"
git push origin main

Notes:

Pull first to get teammate’s changes
Commit your local changes
Push updated code to GitHub
Resolve conflicts if any appear before pushing

