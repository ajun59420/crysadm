# 723
用法

进入系统后先升级源，输入命令

sudo apt-get update

等一会自动下载，输入命令

sudo apt-get install -y git

如果出现bash: sudo: command not found错误，说明没有安装这个程序，直接输入命令

apt-get install -y sudo git

用 cd 命令进入任意可写权限文件夹，输入命令

sudo git clone https://github.com/ajun59420/crysadm.git

等待下载完成，输入命令

cd crysadm && sudo chmod +x setup.sh && ./setup.sh

此时等待安装，完成后会自动启动云监工。

PS:

run.sh是运行脚本，down.sh是停止脚本，setup.sh是安装环境脚本。

默认端口：4000 第一次获得密码方法：浏览器打开【IP:4000/install】 -更新到最新版方法：cd crysadm进入程序根目录; sudo git reset --hard HEAD ; sudo git pull即可
