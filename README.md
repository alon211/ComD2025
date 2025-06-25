#######电脑没有这个项目时###########
1. 创建一个文件夹
2. git init
3. git remote add  origin git@github.com:alon211/ComD2025.git
4. git pull origin master

#######新电脑没安装SSH###########
git Bash 运行以下指令
ssh-keygen -t ed25519 -C "306068447@qq.com"
clip < ~/.ssh/id_ed25519.pub
去GitHub settings里找到SSH ，创建一个新的SSH KEY ，粘体上去，建一个title