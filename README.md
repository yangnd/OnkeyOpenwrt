## OnkeyOpenwrt 基于原生Lean大 OpenWRT 的固件(AS IS, NO WARRANTY!!!)

### 发布地址：
https://github.com/sirpdboy/OnkeyOpenwrt

### 追新党可以在Action中取每日更新（可能会翻车，风险自担）：
https://github.com/sirpdboy/OnkeyOpenwrt/actions

### 本地一键编译命令（注意装好依赖）：
git clone https://github.com/sirpdboy/onekeyopenwrtlean &&cd OnkeyOpenwrt&&bash onekeyopenwrtlean.sh

### 注意事项：
1.IRQ脚本依赖nohup组件，fork后自行魔改的用户请补全依赖

2.登陆IP：192.168.1.1 密码：password

3.OP内置升级可用

4.SSRP使用姿势： ①添加你要的订阅链接 ②再在最后加一行空行 ③右下角点一下保存并应用 ④更新所有订阅服务器节点

5.遇到上不了网的，请自行排查自己的ipv6联通情况，或禁用ipv6（同时禁用WAN和LAN的ipv6）

### 版本信息：
LUCI版本：LEAN当日最新

### 特性及功能：
1.优化界面和菜单分类更直观合理

2.内置二款主题，包含SSRP，openclash，ADBYBY，微信推送，网易云解锁，SmartDNS，网络唤醒，DDNS，UPNP，FullCone(防火墙中开启)，BBR（默认开启）

