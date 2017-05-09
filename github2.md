# GitHub2
##1. 个人主页上的“+”下拉菜单可创建的四种类别分别有？
##2. 分别的意思？
>>+ 新建仓库（new repository）  
+ 导入仓库（import repository）  
+ 新的代码（new gist）  
+ 新建组织（new organization）

##3.  如何能将仓库中的html文件直接解析成页面？
sitting->github pages->master branch

##4.  如何删除仓库
setting->danger zone->delete this repository

##5.  Bash是什么操作系统的命令
linux

##6.  Pwd是什么命令
显示当前路径

##7.  Cd是什么命令
切换当前目录到其他目录

##8.  Echo是什么命令
输出提示信息

##9.  配置git用户名的命令
git config --global user.name [username]

##10.  配置邮箱的命令
git config --global user.email [email]

##11. 命令行换行方式
\（反斜杠）
##12. 命令行终结方式
Ctrl+c
##13. 使用命令行比GUI方式有何优势
便于文件管理，便于列出文件和属性

##14. 提交到本地仓库时为什么有暂存区
>>1.原材料入库，未检验或检验后有疑惑，待处理。

2.成品入库，同上。

3.要领出的东西比较多，为了节约时间，提前做好准备，放在暂存区。

4.入库的库位一时没准备好，暂时放一下。

5.正常检查过程中发现有疑问的物品，暂时放一下。


##15. 新建代码仓库的命令

git init

##16. git clone [url] 这个命令的作用是:克隆


##17. 添加指定文件到暂存区的命令
git add .

##18. 删除工作区文件，并且将这次删除放入暂存区的命令
$ git rm [file1] [file2] ...

##19. 改名文件，并且将这个改名文件放入暂存区的命令
$ git mv [file-original] [file-renamed]

##20. 提交暂存区到仓库的命令
git commit -m[message]
##21. 直接从工作区提交到仓库的命令
git commit -a -m[message]

##22. 显示变更信息的命令
git status
##23. 查看历史信息的命令
git log
##24. Commit的意义是
comiit 是将本地修改保存到本地仓库中
##25. Pull的意义是
取回远程主机某个分支的更新，再与本地的指定分支合并。
##26. Push的意义是
git push 将本地仓库修改推送到服务器上的仓库中
