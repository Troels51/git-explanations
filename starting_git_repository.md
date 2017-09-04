## Starting git repository

### Git global setup
```
git config --global user.name "Troels Dalsgaard Hoffmeyer"
git config --global user.email "troels.hoffmeyer@bksv.com"
```
### Create a new repository
```
git clone https://github.com/Troels51/git-explanations.git
cd git-explanations
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
```
### Create a new repository from existing folder
```
cd existing_folder
git init
git remote add origin https://github.com/Troels51/git-explanations.git
git add .
git commit -m "Initial commit"
git push -u origin master
```
### Upload existing Git repository
```
cd existing_repo
git remote add origin https://github.com/Troels51/git-explanations.git
git push -u origin --all
git push -u origin --tags
```