# Netflix-Clone and GitHub Introduction

### **GitHub Commands**
1. git init - Creates a local directory.
2. ls - LIsts all the files you have in your local directory
4. ls -a - Lists all the files you have in your local directory including the hidden files
5. git add . - Tracks all your changes
6. git reset - Removes the changes you made like un-adding changes.
7. git commit -m "message" - Saves the changes you made for pushing to the remote repository
8. git remote add origin <url of remote repo> - With this command you are connecting your local repository with your remote repository to allow interaction between the two repositories. You use this command when before pushing to your newly created remote repo, as you cannot push to a repo you are not connected to.
9. git pull origin <branch name> - You use this command when you have changes in your remote repo that are not present in your local repo. It allows you to pull those changes to your local repo. If your remote repo has changes that are not present in your local repo, then you will not be able to push any changes to your remote repo due to the differences.
10. git push origin <branch name> - With this command, you are pushing the changes you have in your local repo to the remote repo.
11. git branch - With this command, you are listing all the branches you have in your remote repo. If you have not connected with any remote repo, this command will return nothing. When the branches are being listed, the one you are currently working on will be marked with an astericks.
12. git branch <branch name> - With this command, you are creating a new branch and you give the branch whatever name you want.
13. git checkout <branch name> - This command switches to a new branch. If you have a new branch or many branches, you can switch to any branch with this command and specify the branch name.
    

