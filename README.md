# adding_repo_local_git
add files to git repo via local machine
ssh-keygen
 cd PycharmProjects/
 cd AgileFlow/

 git init
 git remote add origin git@github.com:kishanbulkmro/AgileFlow-Django.git
 
 git remote set-url origin git@github.com:kishanbulkmro/AgileFlow-Django.git
 git remote -v

git status
git add .
git status
git commit -m "first commit"
git status
git push origin master
git push origin master -f
git pull origin master 





branching :
git checkout -b branchname
git commit -a -m 'commit message of branch'
git status
git checkout msater
 git branch -d branchname (delete branch)
