GitHub地址

SSH：git@github.com:yuldong/gitLearn.git

HTTPS：https://github.com/yuldong/gitLearn.git

与 GitHub 仓库进行关联

git remote add origin HTTPS

git remote add test SSH


推行内容至GitHub
git push -u origin master

查看GitHub仓库
git remote -v

移除其中的一个仓库
git remote rm test

设置GitHub连接
git remote set-url origin HTTPS