## GitLabExam

# for configuration
git config --global user.name " " , 
git config --global user.email " "

# to create file 
touch filename

# to add changes to git repo irrespective of files
git add .

# to add changes made in single file 
git add filename

# to commit the change with message
git commit -m "msg"

# push the changes to GitHub repo
git push origin main

# to list the git history with unique commit ID, commit msg 
git log

# to revert the commit
git revert commitId
