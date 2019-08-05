# -Socks5-
搭建一个Socks5代理服务器。

把shadowsock脚本下载到服务器，给予执行权限，然后执行就可以了。

chmod a+x shadowsocks.sh

./shadowsocks 2>&1 | tee shadowsocks.log
