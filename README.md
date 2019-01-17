# V2ray-script  
[原作者](https://233now.com/post/1/) [开源地址](https://github.com/233boy/v2ray)

 下载安装:
 
``` bash
bash <(curl -s -L https://233now.com/v2ray.sh)
```
******
# 更新日志
<b>2018-01-28</b>
* 第一个完善版本发布…

**2018-5-2**
* 支持 HTTP/2 … 懒得发一个版本就在这里写一下

**2018-5-26**
* 支持 Socks5 …

**2019-1-5**
* v3 版本，更加好用了。新年快乐！


# 功能特点

* 支持 V2Ray 多数传输协议

* 支持 WebSocket + TLS / HTTP/2

* 支持 动态端口 (WebSocket + TLS，Socks5， HTTP/2 除外)

* 支持 屏蔽广告

* 支持 配置 Shadowsocks

* 支持 下载客户端配置文件 (不用 Xshell 也可以下载)

* 客户端配置文件同时支持 SOCKS 和 HTTP

* 支持 生成 V2Ray 配置二维码链接 (仅适用部分客户端)


* 支持 生成 Shadowsocks 配置二维码链接

* 支持修改 V2Ray 传输协议

* 支持 生成 V2Ray 配置信息链接

* 支持修改 V2Ray 端口

* 支持修改 动态端口

* 支持修改 用户ID

* 支持修改 TLS 域名

* 支持修改 Shadowsocks 端口

* 支持修改 Shadowsocks 密码

* 支持修改 Shadowsocks 加密协议

* 自动启用 BBR 优化 (如果内核支持)

* 集成可选安装 BBR (by teddysun.com)

* 集成可选安装 锐速 (by moeclub.org)


* 一键 查看运行状态 / 查看配置信息 / 启动 / 停止 / 重启 / 更新 / 卸载 / 等等…

* 人性化向导 & 纯净安装 & 卸载彻底

*******
# 安装或卸载

* <b>要求：Ubuntu 16+ / Debian 8+ / CentOS 7+ 系统</b>

* 推荐使用 Debian 9 系统，脚本会自动启用 BBR 优化。

* 备注：不推荐使用 Debian 8 系统，因为 Caddy 申请证书可能会出现一些莫名其妙的问题