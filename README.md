# Git_Practice
This is a practice repository aiming to enhence the capability to use git in terminal.
I use Ubuntu 14.04 in VMware Workstation to do this practice.
这个仓库主要是使用一个README.md来模拟Git的命令行使用的，参考书籍为日本的大塚弘记的《GitHub入门与实践》。
以前都是主要使用Windows下的Github客户端，轻度使用命令行来解决问题，现在我想要成为一个合格的开元使用者。


## 安装
```
sudo apt-get update
sudo apt-get install git
```
如果现在在命令行输入git后会产生一些提示，说明安装成功

## 设置SSH Key
GitHub上连接已有仓库时的认证，是使用了SSH的公开秘钥认证方式进行的，运行下面的命令来创建SSH Key
$ ssh-keygen -t rsa -C "your_email@example.com"
