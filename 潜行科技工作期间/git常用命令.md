1. git常用命令
分为两种情况

第一种已有仓库：

1、从远程拉取git clone <地址>

2此时我们可以直接在本地文件夹内编辑，添加或者删除文件

3、通过git add <要提交到本地暂存区的文件名>

4、git commit -m "本次提交的注释"

5、git push origin master 将修改提交到远程仓库主分支。

分支的相关知识：

查看分支 git branch

切换分支 git checkout

删除分支 git branch -d <未打开的分支名>

合并分支 git merge <分支名>

合并完分支后还要git push将内容提交到远程

第二种新建仓库：

需要git remote add <仓库地址> 连接远程仓库

查看状态

回退