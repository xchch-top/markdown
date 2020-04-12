#### 将文件移出暂存区, 文件会不被跟踪

git rm --cached filename

#### 输入日志的简洁格式

git log --pretty=oneline

#### 限制提交历史的输出范围

git log --since=2.weeks

#### 将文件的修改从暂存区撤出

git reset HARD filename

#### 丢弃工作区的改动

git checkout -- filename

#### 显示Git存储的每个远程仓库的URL

git remote -v

#### git添加远程仓库

git remote add markdown https://github.com/xchch-top/markdown.git

#### 创建并切换分支

git checkout -b xcc

#### 筛选已经合并到当前分支的所有分支

git branch --merged

#### 查看已经设置了哪些跟踪分支

git branch -vv

#### 删除远程分支

git push origin --delete markdown

#### 把已有仓库导出为裸仓库

git clone --bare git git.git

mv git.git /home/xcc/
#### 从服务器上clone git仓库

git clone root@localhost:/home/xcc/git.git git2

#### LF CRLF 提交检出均不转换

git config --global core.autocrlf false
