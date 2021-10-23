# Git使用教程

*git初始化：* `git init`

添加文件到仓库：`git add someting`

提交文件： `git commit -m '提交说明'`

查看仓库状态： `git status`

查看difference ：`git diff`

提交历史记录：`git log ` or `git log --pretty=oneline` 

回退版本 `git reset --hard HEAD^`

命令历史记录：`git reflog`

回到未来： `git reset --hard 版本号`

`HEAD指向的版本就是当前版本`

删除工作区的修改：`git checkout -- 文件`

暂存区的修改撤销：`git reset HEAD gitUser.md`

删除本地文件：`rm text.txt`

git删除文件 `git rm  text.txt` `git commit -m'remove text.txt'`

git 链接远程仓库： `git remote add origin 地址`

git 推送远程仓库（第一次）：`git push -u origin master`

git 推送远程仓库：`git push origin master`

删除远程库（添加远程库时地址写错）：`git remote rm 名字`

查看远程信息： `git remote -v`

