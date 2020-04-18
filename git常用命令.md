#Git
## 配置
- git config --global user.name "yrion"
- git config --global user.email "yuldong@126.com" 

## 别名
- git config --global alias.st "command"

##查看配置
- git config -l

## 初始化仓库
- git init

## 查看状态
- git status

## 新增文件
- git add .
- git add fileName

## 提交文件
- git commit -m "description"
- git commit -amend `合并缓存的修改和上一次的提交，用新的快照替换上一个提交`

## 一步提交文件
- git commit -a -m "description"

## 查看日志
- git log fileName
- git log --prettty=oneline
- git log -p 
- git log --grep "<pattern>"

## 查看修改的内容
- git diff fileName

## 回退到上个版本
- git reset -- hard HEAD^

## 回退到旧版
- git reset -- hard HEAD~`Number`

## 查看恢复日志 | 提交日志
- git reflog

## 恢复至某个版本
- git reset --hard `commit id`

## 恢复修改的文件(未add)
- git checkout -- fileName

## 恢复修改的文件(已add,未commit)
- git reset HEAD fileName *将内容从暂存库中移除,此后通过命令在工作区中修改*

## rebase
- git rebase -i 交互式调整


