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
