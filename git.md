# git 常用指令
*学习如何用git管理自己的项目，学习git的一些常用指令*
- - -
- **git status**：查看仓库的当前状态
- **git diff \<filename>**：对比文件修改后的差别
*git diff readme.txt*
- **git add \<filename>**：将文件添加到仓库
*git add readme.txt*
- **git commit -m "\<note>"**：将文件提交到仓库
*git commit -m "wrote a readme file"*
- **git log**：查看历史仓库版本
*git log --pretty=oneline*
*head表示当前版本*
- **git reset**：回退版本
*git reset --hard HEAD^*
*git reset --hard HEAD~100*
*git reset --hard 96d60*
- **git reflog**：记录每一次命令
- **git checkout**：撤销修改
*git checkout -- readme.txt*