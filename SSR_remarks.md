# SSR一键安装命令 #
    wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ssrmu.sh && chmod +x ssrmu.sh && bash ssrmu.sh

SSR管理命令`bash ssrmu.sh`

# SS一键安装 #
    wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks.sh
    chmod +x shadowsocks.sh
    ./shadowsocks.sh 2>&1 | tee shadowsocks.log 

# SS相关命令 #

启动：`/etc/init.d/shadowsocks start` 

停止：`/etc/init.d/shadowsocks stop` 

重启：`/etc/init.d/shadowsocks restart` 

状态：`/etc/init.d/shadowsocks status`

配置文件路径：`/etc/shadowsocks.json` 

日志文件路径：`/var/log/shadowsocks.log` 

安装路径：`/usr/local/shadowsocks/shadowsoks`

# SSR相关命令 #

启动：`/etc/init.d/ssr start` 

停止：`/etc/init.d/ssr stop` 

重启：`/etc/init.d/ssr restart` 

状态：`/etc/init.d/ssr status`

配置文件路径：`/etc/shadowsocksr/user-config.json` 

日志文件路径：`/var/log/shadowsocks.log` 

安装路径：`/usr/local/shadowsocks/shadowsoks`