# myRepo
我的第一个仓库
git clone + 地址   从远程仓库下载项目
git add 将文件修改添加到暂存区
git commit -m "提交的说明"  将修改的内容和描述修改的信息一起提交

修改之后使用了git add的命令,但是没有及时使用git commit命令又再次修改了要提交的文件
再次修改了文件

git checkout -- 文件名  可以(丢弃工作区的修改)删除工作区的修改,使其恢复到上一次commit的时候
git add 命令之后又对文件做了修改,使用 git checkout -- 文件名 可以丢弃此次的修改,恢复到add命令之后

git rm 文件名 可以删除该文件(需要使用 git commit 进行提交)
如果没有使用commit命令之前,可以使用git checkout -- 文件名 再次找回来

使用git branch 分支名称  表示创建一个名称为xx的分支
使用git checkout 分支名称   表示从当前分支切换到名称为xx的分支

在dev分支上进行修改并提交