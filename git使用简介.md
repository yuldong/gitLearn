配置全局用户名以及邮箱：

git config --global user.name "yuldong"

git config --global user.email "yuldong@126.com"

查看配置信息：
git config -l

查看当前仓库状态：
git status

提交之前将文件添加到暂存库
git add fileName

将文件提交至主干
git commit -m "注释"

综合提交并注释
git commit -a -m "注释"

查看提交日志信息
git log fileName

将所有文件添加到暂存库中
git add .

文件内容对比
git diff fileName

查看提交的信息并整理方便查看
git log --pretty=oneline

回退到某个版本
git reset --hard HEAD~1

撤销回退的操作
git reset --hard commitID

查看提交的commitID
git reflog

恢复（针对未提交至暂存库）
git checkout --fileName

恢复,从暂存区中退出（针对已提交至暂存库，但为提交至主干）
git reset HEAD fileName（将暂存区的内容恢复到工作区）
git checkout --fileName

删除文件
del fileName

恢复删除文件后只能通过commitID进行恢复
git reset --hard 

暂存分支
git stash
