# 1
sudo apt update
# 2
sudo apt install software-properties-common
# 3
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

# 载入本脚本
wget -c https://github.com/xhjvpn/dd/releases/download/dd/dd.tar.gz -O - | tar -xz

# 打开路径
cd dd

# 安装依赖
pip3 install -r requirements.txt

# 安装pip+pip3
python3 d1.py

# 运行攻击
python3 dd.py
