# 1、 Git介绍
********git*********
* git它是一个分布式版本控制工具
* git安装 基于官网发布的版本
* git命令
* git分支 
* idea 集成git
***********github***********
创建远程库
代码推送 push
代码拉取 pull
代码克隆 clone
SSH免密登录
Idea集成Github
**********gitee码云**********
码云创建远程库
idea集成Gitee
码云连接Github 进行代码赋值和迁移
**************gitlab***********
gitlab服务器的搭建和部署
idea集成Gitlab

* Git和SVN区别

* Git安装

# 2、Git常用命令
(ls 显示当前文件夹中的所有内容（显示普通目录）)
(ls -a 显示所有目录（包括隐藏内容）)
(cat 查看文件里面有什么内容)
(ctrl+l 清屏)
* 1、设置用户签名
* git config --global user.name  设置用户签名
* git config --global user.email
<br>

* 2、初始化本地库
* 我们希望一个文件夹本git管理的化，那么就要在一个文件夹下进行git初始化
* 找一个希望被git管理的文件夹
* 然后右键，点击git bsh here
* git init 初始化本地仓库
<br>

* 3、git工作区、暂存区和版本库、托管平台
* 工作区：项目目录，项目目录下隐藏了一个.git目录，这个目录不属于工作区，而是版本库
  || 工作区代码先提交到暂存区
* .git目录 版本库（本地仓库）
* * 暂存区（又叫做历史区） 暂时保存
  || 提交
* * master 主分支 记录产生
  ||
* Github远端库（托管平台）
* * 局域网 gitlab
* * 外网   gitlab  github gitee
<br>

* 4、git add 文件名
* git add 加入暂存区（只是将文件复制了一份）
* git add . (表示将当前工作区的所有文件（修改的）添加到暂存区里面)
* git add 文件夹名/ (表示将单独的一个文件夹放入暂存区)
<br>

* 5、git status
* 绿色字体 表示在暂存区
<br>

* 6、git rm --cached 文件名
* 从暂存区中文件（移除后文件名为红色，表示只在工作区存在）
<br>

* 7、git commit 把暂存区的（所有）内容放到历史区
* git commit -m '我是第一个版本' (-m是注释的意思)
<br>

* 8、git log 
* 查看提交到版本区的历史记录