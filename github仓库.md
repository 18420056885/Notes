### ==1、安装git==
##### 检查是否已安装
git --version

### 如果没安装，就安装 Git
sudo apt update
sudo apt install git

### ==2、克隆本地仓库==
###### 进入你想要存放的目录
cd ~（表示进入主目录）  
或者 cd ~/桌面 或其他目录

##### 克隆你的仓库（使用HTTPS链接）
git clone https://github.com/18420056885/obsidian_mdgit.git


### ==3、提交到 master 分支并推送新文件==
##### 添加所有新文件
git add .

##### 提交更改
git commit -m "首次提交 Obsidian 笔记"

##### 设置你的用户名
git config --global user.name "18420056885"

##### 设置你的邮箱（用 GitHub 注册邮箱）
git config --global user.email "3027885446@qq.com"

##### 创建并切换到 master 分支
git checkout -b master

##### 推送到 GitHub（使用 master 分支）
git push -u origin master

用户名：18420056885
个人令牌（key words）：见微信

### ==4、永久设置 Git 存储凭据==
##### 永久存储（加密的）
git config --global credential.helper store

##### 推送一次（输入用户名和令牌，之后会自动记住）
git push -u origin master

