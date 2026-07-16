# Learn-Git
## This project is to learn about version control systems

Reference youtube video :https://www.youtube.com/watch?v=RGOj5yH7evk&t=317s  
#---------------------------------------------------------------------------------------------------
### 1.Cloning a GitHub repo:

  git clone HTTPS_url or git clone SSH_key 

- For this you have to setup SSH key: key that connect your local repository with the GitHub account  
- For complete guidance on how setting up SSH key Reference:https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account )  
- generate SSH key windows/vscode : **ssh-keygen -t ed25519 -C "youremail@gmail.com"**
- Copy SSH key to clipboard windows/vscode command: **cat ~/.ssh/id_ed25519.pub | clip**  
[clip < ~/.ssh/id_ed25519.pub command may cause ParserError]

### 2. To check available files in the considering directory including hidden files:
   on windows vscode/powershell: Get-ChildItem -Force  
   on macos : ls -la  
  
### 3.Basic git commands  
git status - check status of the git  
git add .  - allow all availble files to track by git  
git commit -m "message1" -m "message2" -save filesin git  
git config user.email "emailaddress" >>to set the identity only in this repository  
git config --global user.email "emailaddress"  
git push - upload git commits to remote repository :)  
git init - create a local folder initialising it as a githubrepo
git pull - importing changes from the remote repo  
git remote add origin SSH_KEY - connecting locally created repo with online repo  
git remote -v -show any repo that remotely connected  
git checkout -b branch-1 -create a new branch  
git checkout main - switch between branches  
git branch - show all available branches and specify the current branch


## Branch 2 is Created!