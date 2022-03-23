# Linux-

# 删除程序进程
kill -9 项目编号
# 查看GPU信息
watch nvidia-smi

# 删除文件夹实例：将会删除/var/log/httpd/access目录以及其下所有文件、文件夹
rm -rf /var/log/httpd/access

# 可以给 zip 文件解压到当前文件夹。
unzip zipped_file.zip

# 管理员模式
# 管理员模式查看各个用户内存使用情况
du -sh *
# linux用户与用户之间传输文件
scp -r /home/data/MMEW liaoleqing@202.195.239.96:/home/liaoleqing
# 挂盘
sudo mount /dev/sdb /home/academy/
