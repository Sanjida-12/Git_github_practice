1. What is git
Answer: Git is a version control system. It contains the code you are writing on your local machine. It helps you to keep your code secure and always track the changes you are making.

2. How to setup git 
Answer: Download git from git official website then install it.

3. Git configuration
Command Prompt: (To tell git who you are)

1. git config --global user.name "your name"
2. git config --global user.email "your email"
3. git config --global user.password "your password"
4. git config --global core.editor "code --wait" (set vs code default to avoid scary vim editor, --wait to wait vs code untill you close)
5. git config --global core.editor -e (Open to edit global config file in vs code)
6. git config --global core.autocrlf true (to fix new line issue between windows and mac ios)



Command Prompt: (To use git)
1. git status (to check the current status)
2. git init (to initiate git into the folder/rpository )
3. git add . (to track/add all the changes to commit)
4. git commit -m"message" (to comment about your changes)
5. git remote add origin "remote repository name (copy link from github)"
6. git remote --v (to see the remote repository location if its added or not)
6. git push -u origin master (only for 1st  time)