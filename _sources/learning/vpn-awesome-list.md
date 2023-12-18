# VPN Awesome List

## XMRth

- [XMRth](https://xmrth.cc/)
- [XMRth公告板 (xmrth1.net)](https://xmrth1.net/)

## 自建代理

1. 在Azure上创建一台Ubuntu VM，注意采用用户名/密码方式登陆。
设置服务器打开443和22端口
2. 下载Putty：https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
3. 通过Putty输入用户名密码连接远程服务器
4. 参考文章https://teddysun.com/358.html 执行命令进行安装，并设置端口443
5. 通过收集访问https://github.com/shadowsocks/shadowsocks-android/releases 下载安卓客户端并安装
6. 在安卓App中设置IP和端口号进行连接即可

---

ShadowsocksR(SSR)一键安装脚本 By 秋水逸冰-王超博客 (wangchao.info)

sudo su
wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocksR.sh
chmod +x shadowsocksR.sh
./shadowsocksR.sh 2>&1 | tee shadowsocksR.log
Edge
about:flags
Anonymize local IPs exposed by WebRTC -> Enabled

系统代理模式 > 全局模式
代理规则 > 全局

Release v4.9.2 · shadowsocksrr/shadowsocksr-csharp · GitHub