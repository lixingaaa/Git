git init 把这个目录变成Git可以管理的仓库
git add <file> 添加文件添加到仓库
git add <file> --all 添加全部文件到仓库
git status 查看状态
git commit -m <message>  文件提交到仓库
git log 命令显示从最近到最远的提交日志
git reset --hard HEAD^ 回退到上一个版本
git reset --hard 版本号 回到指定版本
git reflog 记录每一次命令
git checkout -- <file> 丢弃工作区的修改
git reset HEAD <file> 可以回退版本，也可以把暂存区的修改回退到工作区
git rm <file> 删除文件
git remote add origin git@github.com:用户名/git仓库名称
git push -u origin master 本地库推送到远程分支