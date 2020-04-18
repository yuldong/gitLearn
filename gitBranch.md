git branch <branch>

git checkout <branch>

git branch

git checkout -b <branch>

git branch -d <branch> `这是一个安全的操作，Git 会阻止你删除包含未合并更改的分支。`

git branch -D <branch> `强制删除指定分支，即使包含未合并更改。`

git merge <branch>

git push origin --delete <branch>

git branch -m <old-branch-name> <new-branch-name>

git branch -f <branch-name> <commmitId> **将分支强制移动到`指定位置`**

git branch -a
git branch -r
git branch -l

git push origin :emptyBranchName

git log --graph --pretty=oneline

git merge --no-ff -m "no fast forward" BranchName

git log --graph --pretty=oneline --abbrev-commit

git stash

git stash list

git stash apply 

git stash drop

git stash pop

git diff master >PatchName

git apply PatchName

git fetch 

git pull

git checkout "commitid"

git reset **慎用**

git revert **保留提交历史，只撤销对应的历史操作**

**撤销(revert)被设计为撤销 公开 的提交的安全方式，git reset被设计为重设 本地 更改。因为两个命令的目的不同，它们的实现也不一样：重设完全地移除了一堆更改，而撤销保留了原来的更改，用一个新的提交来实现撤销。**

git clean -f

git branch --set-upstream-to=origin/BranchName



