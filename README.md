# Netflix-Clone and GitHub Introduction

### **GitHub Commands**
1. ```git init``` - Creates a local directory.
2. ```ls``` - LIsts all the files you have in your local directory
4. ```ls -a``` - Lists all the files you have in your local directory including the hidden files
5. ```git add .``` - Tracks all your changes
6. ```git reset``` - Removes the changes you made like un-adding changes.
7. ```git commit -m "message"``` - Saves the changes you made for pushing to the remote repository
8. ```git commit -am "message"``` - With this command, you are doing both the adding and committing at the same time, and that is specified in the -am argument. But this command will not add new files it will only add changes of the files that were already tehre and commit them.
9. ```git remote add origin <url of remote repo>``` - With this command you are connecting your local repository with your remote repository to allow interaction between the two repositories. You use this command when before pushing to your newly created remote repo, as you cannot push to a repo you are not connected to.
10. ```git remote -v``` - This com and lists all the remote repositories you are connected to.
11. ```git pull origin <branch name>``` - You use this command when you have changes in your remote repo that are not present in your local repo. It allows you to pull those changes to your local repo. If your remote repo has changes that are not present in your local repo, then you will not be able to push any changes to your remote repo due to the differences.
12. ```git push -u origin <branch name>``` - With this command, you are pushing the changes you have in your local repo to the remote repo.
13. ```git branch``` - With this command, you are listing all the branches you have in your remote repo. If you have not connected with any remote repo, this command will return nothing. When the branches are being listed, the one you are currently working on will be marked with an astericks.
14. ```git branch <branch name>``` or ```git checkout -b <branch name>``` - With this command, you are creating a new branch and you give the branch whatever name you want.
15. ```git checkout <branch name>``` - This command switches to a new branch. If you have a new branch or many branches, you can switch to any branch with this command and specify the branch name.
16. ```git diff``` - With this command you can see the changes that were made to the files.
17. ```git clone <url of remote repo>``` - With this command you are copying files from a remote repo to your local machine and also creating a git repository. So when you use this code there is no need for you to use git init as the cloned repo will already be a git repository. Also, you do not need to add/connect to the remote repo using ```git remote add origin <url of remote repo>``` because you are already connected to it when you clone.
    

