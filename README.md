# Git命令大全

|命令|功能|
|---|---|
|git config -l|查看所有配置|
|git config --system --list|查看系统配置|
|git config --global --list|查看本地配置|
|git config --global user.name "用户名"|设置用户名|
|git config --global user.email 邮箱地址|设置邮箱地址|
|git init|将某个目录初始化为git目录|
|git clone [github或gitee链接]|从远程克隆项目|
|git status 文件名称|查看文件状态|
|git add .|增加所有文件到暂存区|
|git commit -m "提交信息" |提交暂存区中的内容到本地仓库，-m：提交信息|
|git reset|回退版本|
|git push -u origin master|提交代码到远程git库|
|git pull|拉取文件到本地|
|git log|查看日志|
|git branch|查看所有本地分支|
|git branch -r|查看所有远程|
|git branch 分支名称|新建分支，但留在当前分支|
|git checkout 分支名称|切换到指定分支|
|git checkout -b 分支名称|新建并切换到该分支|
|git merge 分支名称|合并指定分支到当前分支|
|git branch -d 分支名称|删除本地分支|
|git push origin --delete 分支名称|删除远程分支|
|git branch --dr|删除本地与远程分支|

---
# Git总结

>修改git文件夹下的config文件，增加用户名密码，实现自动提交
>
>**Github:**
>
>`https://用户名:密码@github.com/happyonee/learngit.git`
>
>**码云：**
>
>`https://用户名:密码@gitee.com/happyonee/learngit.git`
