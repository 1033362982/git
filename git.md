#git/svn工具
##Git是一款免费、开源的分布式版本控制系统，用于敏捷高效地处理任何或小或大的项目。
##1.创建本地仓库并初始化git init,该命令把这个目录变成Git可以管理的仓库； 
##2.ls查文件夹
##3.把本地仓库传到网上分为编辑区，暂存区，主分支
##4.git status若为红色，则说明在编辑区
##5.添加到缓存区：git add . 若为绿色，变成暂存区
##6.把暂存区提交到主分支：git  commit -m "first commit"
###git config --global user.email"",
##git remote -v:看远程主机名
##git push -u origin master:同步到线上仓库
##解决冲突步骤：
###(1)新建文件夹home office;新建text.html保存到officce中；在office中右键git  bash here输入"git init"-"git push -u"
###(2)在git hub中新建项目，office中提交后clone  or download;在homr文件夹中git bash here输入git clone+网址;在branch中新建html文件，执行git add .到git commit命令
###(3)把其中一个文件home做改动后，git push -u origin master;在另一个office文件中git pull,执行完这些操作以后起冲突
###(4)解决冲突：在office文件夹中git  pull，修改完以后从新执行git  add到git push步骤
##建立分支
###步骤：
####(1)新建branch文件夹，建立html文件meng..html;
####(2)在该文件夹下git clone+地址，并上传，执行git add .到git commit 步骤
####(3)建立zhang分支，git checkout 可从主分支切换到分支；
####(4)在html文件中改动，执行git add .到git commit 步骤；git checkout master切换到主分支；
####(5)git merge+zhang合并；
####(6)上传，先上传master,执行git  push -u origin master;git checkout zhang;it  push -u origin zhang

