输入ssr安装命令，复制下面整段(鼠标右键即可粘贴)
wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocksR.sh
chmod +x shadowsocksR.sh
./shadowsocksR.sh 2>&1 | tee shadowsocksR.log



卸载方法：
使用 root 用户登录，运行以下命令：
./s-sR.sh uninstall安装完成后即已后台启动 s-sR ，运行：
/etc/init.d/s-s status可以查看 s-sR 进程是否已经启动。
本脚本安装完成后，已将 s-sR 自动加入开机自启动。
使用命令：
启动：/etc/init.d/s-s start
停止：/etc/init.d/s-s stop
重启：/etc/init.d/s-s restart
状态：/etc/init.d/shadowsocks status
配置文件路径：/etc/s-s.json
日志文件路径：/var/log/s-s.log
代码安装目录：/usr/local/s-s

[安装锐速命令]
wget -N --no-check-certificate https://github.com/91yun/serverspeeder/raw/master/serverspeeder.sh && bash serverspeeder.sh 

