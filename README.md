# Git Course
>**This repository is made for educational purposes.**

### How to create a repository into your machine
1. Create a repository on github website
2. get the repo HTTPS code and it must be as the following formula https://github.com/ `UserName` /`Repo Name`.git
   - replace `Username` with yours and `Repo name` with your repository name
   - it must end with **.git**
3. Create a folder on your pc and open your command line in this folder and type the following command
   - git clone https://github.com/ `UserName` /`Repo Name`.git
   - replace `Username` with yours and `Repo name` with your repository name
   - it must end with **.git**

## Please Refre and study this image 
![1_tjrF1ff5UjVNclwwe_GREg](https://github.com/user-attachments/assets/958f3ad1-91ee-4a6c-b311-6dfca2b66e42)


## Config your github account
-   git config --global user.email "you@example.com"   Ex: git config --global user.email "asticalaa1@gmail.com"
-   git config --global user.name "Your Name"          Ex: git config --global user.name "Mahmoud Alaa"


## Some Important Commands
1. git add
2. git commit -m `"Your Message"` **Please note: You must put a message**
3. git status  **to get the inforamation about your tracked and untracked files**
4. git push `Remote name` `Local Branch`
   - To get local branch excute: git branch
   - To get remote branch excute: git remote -v
   - **Please note: You can't push unless you have the latest changes from the remote**.
   - **to pull and push at the same time use `git push -u "Remote name" "Local Name"`**

5. to unstage from **staging area** to **workspace**: git restore --`File name`
   
6. git pull `Remote name`  "updates your local files to the remote files"

## Git Configuration
**Any configuration command starts with git config**

### to set VS code the default editor of configuaration settings
`git config --global core.editor "code --wait`
### for starting to edit
`git config --global -e`
![image](https://github.com/user-attachments/assets/e6dfa7a3-8e47-48ba-bce7-735e49462547)

#Add existing project to existing repo
Run your terminal at the project path and exctue these commands line by line
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/`username`/`repo name`.git
- git push -u origin main


