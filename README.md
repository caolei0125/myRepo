# myRepo
我的第一个仓库
git clone + 地址   从远程仓库下载项目
git add 将文件修改添加到暂存区
git commit -m "提交的说明"  将修改的内容和描述修改的信息一起提交

修改之后使用了git add的命令,但是没有及时使用git commit命令又再次修改了要提交的文件
再次修改了文件

git checkout -- 文件名  可以(丢弃工作区的修改)删除工作区的修改,使其恢复到上一次commit的时候
git add 命令之后又对文件做了修改,使用 git checkout -- 文件名 可以丢弃此次的修改,恢复到add命令之后