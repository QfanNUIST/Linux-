# Linux-

# 删除程序进程
kill -9 项目编号
# 查看GPU信息
watch nvidia-smi

# 删除文件夹实例：将会删除/var/log/httpd/access目录以及其下所有文件、文件夹
rm -rf /var/log/httpd/access

# 可以给 zip 文件解压到当前文件夹。
unzip zipped_file.zip

# 查看当前目录下文件数目
# 1. 查看当前目录下文件个数
ls -l |grep "^-"|wc -l  
# 2.查看当前目录下，所以文件个数，包括当前目录下子文件夹中的所以文件。　
ls -lR|grep "^-"|wc -l 
# 3.  查看当前目录下文件夹的个数
ls -lR|grep "^d"|wc -l　（文件夹个数）

# 管理员模式
su headoop
# 管理员模式查看各个用户内存使用情况
du -sh *
# 查看可用盘
sudo fdisk -l
# linux用户与用户之间传输文件
scp -r /home/data/MMEW liaoleqing@202.195.239.96:/home/liaoleqing
# 挂盘
sudo mount /dev/sdb /home/academy/
挂上自己的盘
cd ..
sudo mkdir lyj_data
sudo chmod 777 lyj_data/
sudo mount /dev/sdb lyj_data/
# 建用户
useradd -m yangyuze -g student -d /home/yangyuze -s /bin/bash
sudo passwd yangyuye

# 关闭服务器
shutdown -h now
# 开启服务器
reboot
