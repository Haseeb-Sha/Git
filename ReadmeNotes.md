# when you want to clone repo on git and do changes
git clone repo.git
git config 
git branch 
git status 
git add file name or .
git commit -m "message"
git push 
git log
# when you have local repo and want to push to git 
git init
git status
git add .
git config --global user.email "abc@gmail.com"
git commit -m "messgae"
git remote add origin url.git
git push --set-upstream origin master
git push 

# Creating branches (Either in remote or local)
git checkout master
git checkout -b "use feature"
git push --set-upstream origin branch_name
git pull 
git checkout branch_name

# Creating pull Request( allowing senior to cross verify and merge to master)
in another branch 
git add. git commit -m
then on UI
create merge or pul request ( you can check in on UI the changes)
either approve or cancel (with comments)
approve and merge

# Deleting branches
two option , one merge and delete then branch or merge leave as it is
git checkout master
git checkout -d beanch_name
git pull

# Git Rebase( Avoiding Merge merge branch commits git pull then push)
pushed two commits ( one by user and merge commit)
in order to avoid this we use
git pull -Rebase
git push
this stacks up you commit and another commit , saving changes of one commit to another)

# Resolving Merge Conflicts 
>>>>>>> 3e1c5f1 (fina boss)
git checkout master 
git pull 
git merge dev
git push
        by using git rebase
git pull -r 
resolve merge conlficts viewing the file
git rebase --continue 
git push 
