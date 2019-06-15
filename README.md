# git-basico
Comandos básicos do git


Command line instructions
Git global setup

git config --global user.name "username"
git config --global user.email "user@mail"



Create a new repository

git clone http://xxx.git
cd xxx
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master



Existing folder or Git repository

cd existing_folder
git init
git remote add origin http://xxx.git
git add .
git commit
git push -u origin master
