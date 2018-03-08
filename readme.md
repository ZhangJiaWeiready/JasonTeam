1. 新建一个文件夹用自己名字小写字母命名
2. 在这个文件夹内部 鼠标右键菜单 Git bash here
3. git init
4. git clone https://github.com/Jason-Han1/JasonTeam
5. git checkout -b 名字全拼小写
6. git branch 如果显示了你刚才创建的分支就ok了
7. vi test.txt 
8. 进去输入 i 或者 Ins（插入键）随便写点文字
9. 然后按esc 
10. 然后按shift+： 
11. 然后按wq
12. git add test.txt
13. git commit -m "xx完成了xx功能"
14. git status 如果test.txt显示的是绿色的就没问题
15. git push origin 分支名  如果可以正常上传那就ok了
![](https://i.imgur.com/aXiU151.png)
##本地的这个以你名字命名的文件夹就是你以后的工作目录。你的项目就放到这个文件夹底下就可以。任何文件的修改和删除在本地进行就可以。完事了重复12-15的上传步骤就可以，服务器可以自动给你同步。先上项目地址https://github.com/Jason-Han1/JasonTeam
可以查看项目进度以及自己和别人的分支：如下图，点击可以切换分支，如果看到了自己的分支就完全没有问题了。
![](https://i.imgur.com/skt9mIk.png)
###注意：每次做完不要忘记上传，本地文件下除了.git文件夹不要随意修改和删除以外，其他文件都没问题，正常做完上传就是12-15步，只要文件有修改就可以上传不会产生冲突。
![](https://i.imgur.com/pTeJkwP.png)
###每次上传之前看看是不是在自己分下面（hanlitao）就是自己的分支，如果是master或者其他的就要切换到自己的分支，命令 git checkout 分支名，分支命名错了可以使用git branch -d 分支名 删除分支，在进行创建。
![](https://i.imgur.com/D9RRJRP.png)