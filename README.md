# Git
使用Git

# 生成静态网页
http://www.cnblogs.com/DaisyWang/p/5468761.html

# Github使用 for Windows
http://youngxhui.github.io/2016/05/03/GitHub-for-Windows%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B(%E4%B8%80)/

http://youngxhui.github.io/2016/05/13/GitHub-for-Windows%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B(%E4%BA%8C)/

http://youngxhui.github.io/2016/05/15/GitHub-for-windows%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B%EF%BC%88%E4%B8%89%EF%BC%89/

http://youngxhui.github.io/2016/08/28/GitHub-for-Windows%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B%EF%BC%88%E5%9B%9B%EF%BC%89/



在GitHub里面创建文件夹的Amazing的方式:

在要创建的栈路径下Create new file

然后由于GitHub里文件夹为文件的一种，直接在名称输入想要创建的文件夹的名称，然后加入/即可


# SSH密钥生成查看保存
ssh-keygen -t rsa -C "输入用户名"

一路回车+y

cd ~/.ssh

ls (查看此目录下是否有公钥id_rsa.pub和私钥id_rsa)

cat id_rsa.pub (查看公钥内容)

复制下来添加即可

# VMware Workstation Pro 14
安装虚拟机

VMware Workstation 14 Pro永久激活密钥

CG54H-D8D0H-H8DHY-C6X7X-N2KG6

ZC3WK-AFXEK-488JP-A7MQX-XL8YF

AC5XK-0ZD4H-088HP-9NQZV-ZG2R4

ZC5XK-A6E0M-080XQ-04ZZG-YF08D

ZY5H0-D3Y8K-M89EZ-AYPEG-MYUA8

# Linux虚拟机下更新VisualStudioCode
下载.tar.tz文件后进入对应目录，使用tar -xzvf命令解压

# Linux下给予文件夹所有权限
chmod -R 777

# 移动文件夹
sudo mv (文件名) /(路径)

# 提交过程
## 添加ssh公钥
https://blog.csdn.net/shog808/article/details/76563136
## 在配置好用户信息后
（$ git config --global user.name "John Doe"
    
 $ git config --global useer.email johndoe@example.com)
## 提交代码
提交前 scp -p -P 29418 xxx@120.26.125.172:hooks/commit-msg .git/hooks/，xxx是Gerrit用户名，此命令的目的是自动生成changeId；

git add：把要提交的所有修改放到暂存区（Stage）

git commit：一次性把暂存区的所有修改提交到分支

提交时 git push origin HEAD:refs/for/xxx，xxx是真正的远端分支名(dev/dev-stable)
 
 
