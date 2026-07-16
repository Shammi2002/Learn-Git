# Learn-Git
## This project is to learn about version control systems

Reference youtube video :https://www.youtube.com/watch?v=RGOj5yH7evk&t=317s

Cloning a GitHub repo:
 
git clone HTTPS_url or git clone SSH_key 

-for this you have to setup SSH key: key that connect your local repository with the GitHub account
-for complete guidance on how setting up SSH key Reference:https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account )
-generate SSH key windows/vscode :ssh-keygen -t ed25519 -C "youremail@gmail.com"
-copy SSH key to clipboard windows/vscode command: cat ~/.ssh/id_ed25519.pub | clip 
[clip < ~/.ssh/id_ed25519.pub command may cause ParserError]

To check available files in the considering directory including hidden files:
on windows vscode/powershell: Get-ChildItem -Force
on macos : ls -la

Basic git commands
git status - check status of the git
git add .  - allow all availble files to track by git
git commit -m "message1" -m "message2" -save filesin git
git config user.email "emailaddress" >>to set the identity only in this repository
git config --global user.email "emailaddress" 
git push - upload git commits to remote repository :)
git init - create a local folder initialising it as a github repo 
  