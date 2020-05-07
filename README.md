# Git 指令
### git init 初始化仓库
### git add ./ 提交
### git commit -m '注释' 注释
### git status 查看状态
### git diff 跟踪提交状态
### git commit 提交长注释
### git commit a -m 直接提交并暂存
### git log 查看提交日志
### git log --pretty=oneline 产看提交记录 git log --oneline
### git rm 文件  删除工作目录中文件，再将提交到暂存区
### git mv 文件  重命名文件，再将提到暂存区
### git reflog 查看所有操作
###  注释： 每次切换分支钱，当前分支一定要是干净（已提交状态）
###  坑：  在切换分支是，如果当前分支上有未暂存的修改，或者提交的暂存
###       切换成功，但是这种污染主分支


--------------------------------------------------------------

##   branch（分支）
###  git branch 'name' 创建分支
###  git branch 产看分支
###  git branch -a 产看所有分支
###  git checkout 切换分支
###  git branch -d 删除分支（不能自身删除） -D 强制删除
###  git branch -v 
###  git branch -vv 看看是否连接
###  git branch name hashvalue (时光穿梭机) 版本穿梭，回滚到想去地方
###  eg: git branch 'fenzhi' 07bcn11
###  git checkout -b ‘name’ 直接创建加切换到当前分支
###  git merge name 合并分支 eg： 注意合并的时候 请切回到他的 主分支（或者说是上一级）


---------------------------------------------------------

## 项目
### git init 初始化仓库
### git add ./ 提交
### git commit -m '注释' 注释
### git status 查看状态
### git fetch origin 更新远程仓库
### git push  origin 上传合并远程仓库
### git remote -v  查看本地 所有远程目录





