# demo-repo

## git commands:

git clone https://github.com/kwokkawai/demo-repo.git

git add .
git add <filename>
git commit -m "update"
git push 
git push origin master
SSH https://help.github.com/en/github/aut...

git pull 

## demo-repo2

git init
git add .
git commit -m "update"
git remote add origin https://github.com/kwokkawai/demo-repo2.git

# Feature Batch

# Local Development
git checkout -b feature-1-1  
git branch
git checkout master
git checkout feature-1-1  

#some local development

git status
git add README.md
git commit -m "updated README"

git checkout main
git diff feature-1-1
git push --set-upstream origin feature-1-1

#doing code review from github

#update code in local after merge
git pull origin main

# delete branch
git branch -d feature-1-1


# Solving conflick
git checkout -b quick-test

##modify file on quick-test branch

git status
git diff
git commit -am "update index.html"

git checkout main

##modify file on main branch

git branch

git checkout quick-test => error

git commit -am "update master branch"

git checkout quick-test

git diff main

git merge main => conflict 

## edit the conflict files

git diff

git commit -am "update the conflict"


#Make mistake, Undo Stage
<<<<<<< HEAD

## modify the file

git status

git add index2.htmk

git status

git reset

git commit -am "update status"

git reset HEAD~1

git log

#git reset HASH
git reset bc7346e4022413537ebf98584df7275d15525b48

#all changes not just unstage but commit remove
git reset --hard HEAD~1

#fork


=======
>>>>>>> e439e2bd886743ad40d1a2a017a6e265512358c6
