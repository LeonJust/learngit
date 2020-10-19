Git is a distributed version control system.
Git is free software.

git init

git add filename.fileformat 

git status

git diff

git commit -m "description"

git cmd 出现end，q退出

git log

git log --pretty=oneline

git reset --hard HEAD~

git reset --hard cb31

git reflog


//wrong before git add
git checkout -- file

//wrong after git add and before commit
git reset HEAD <file>

//wrong after git commit
git reset --hard <_versiong_number_>

//wrong code for demo

git rm <file> ~~git add <file>

远程仓库
git remote add origin <url>
git push -u origin master
//第一次带-u
git push origin master
//以后不用带-u

//ssh的生成一直没有问题，是没法用cmd或者vscode输入cat指令，所以无法直接读取.pub文件的信息


分支管理
git checkout -b dev

git branch

git checkout dev
git checkout master

git merge dev

git breanch -d dev

git switch dev

git switch -c <new branch name>

//fix bug code

git stash

git stash list

git stash apply/git stash drop
git stash pop

git log --graph --pretty=oneline --abbrev-commit

bug分支


git cherry-pick 4c805e2

开发一个新feature，最好新建一个分支；

如果要丢弃一个没有被合并过的分支，可以通过git branch -D <name>强行删除。



//    master分支是主分支，因此要时刻与远程同步；

//    dev分支是开发分支，团队所有成员都需要在上面工作，所以也需要与远程同步；

//    bug分支只用于在本地修复bug，就没必要推到远程了，除非老板要看看你每周到底修复了几个bug；

//    feature分支是否推到远程，取决于你是否和你的小伙伴合作在上面开发。
