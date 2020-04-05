
## 简单命令   
`pwd 当前目录  
ls 当下目录文件  
cd 进入哪里哪里  
su root 启用root模式  `

`mkdir 创建文件夹  
touch 创建文件  
rm 删除文件  
mv 移动文件  
gedit 文本编辑  
vi 编辑.c文件  
Esc 指令模式（弹到最下面）  
:w   保存文件  
:w file 将修改另外保存到file中  
:w!   强制保存  
:wq  保存文件并退出vi  
:wq! 强制保存文件，并退出vi  
:q 不保存文件，退出vi  
:q! 不保存文件，强制退出vi  
:e! 放弃所有修改，从上次保存文件开始再编辑  `

`halt 关机  
hwclock 看时间  
hwclock(clock) --set --date="11/13/2017 09:26:00" 改硬件时间  
hwclock(clock) --hctosys 系统时间=硬件时间  
hwclock(clock) --systohc 硬件时间=系统时间  `

`gcc 原文件名.c 原文件名.c 原文件名.c(-o 新文件名)   （多文件编译）  
g++ 原文件名.cpp (-o 新文件名)  `

`sudo passwd Ubuntu设置新root密码  
sudo apt-get install vim-gtk Ubuntu安装vim  
sudo nautilus Ubuntu图形界面打开root的文件管理器  `

`ps aux 看进程
kill -9  进程号  杀进程
客户端:  > nohup.out  清空
vim nohup.out  查看
rm 删除文件
rm -r 删除文件夹
nohup 命令 &      后台运行（最后记得回车
stat   文件信息
ctrl + c   终止
ctrl + z  暂停
bg  后台运行暂停的任务
fg 运行后台/暂停的进程（之前登陆的终端的看不见
（win上）pscp D:\feng\bc\py\y\v2(linux).py root@121.41.131.131:/root/study-v2 传py文件到服务器上（上传单个文件
（win上）pscp -r root@121.41.131.131:/root/study-v2/saved2_networks D:\feng\bc\py 下载服务器的网络（下载文件夹
pip3 install 安装python包
exit 退出
chmod -R 755 html 网站文件放到/var/www/html里时，由于html是root复制过去的，权限可能不对，用这个给权限。 
搭ftp的时候， vsftpd.chroot_list 要加用户名； vsftpd.conf 里加上 pasv_address=(外网ip) ，改成listen=YES，listen_ipv6=NO。这三条是被动模式。
安全组也要加20~21 和1024~65535两个端口。`
