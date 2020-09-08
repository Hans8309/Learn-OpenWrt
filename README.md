# Learn-OpenWrt
OpenWrt Basic knowledge

Openwrt 系统刷机，或者在线升级后。进入ssh执行：
1. firstboot -y && reboot now
或者：
2. umount /overlay && jffs2reset && reboot now
这样可以重置 overlay ，免除各种奇怪的问题


# 关闭ipv6，uci大法:
uci delete network.lan.ip6assign

uci delete network.wan6

uci delete dhcp.lan.ra

uci delete dhcp.lan.dhcpv6

uci delete dhcp.lan.ndp

# --------------------
OpenWRT基本知识整理
http://www.openwrt.pro/post-170.html
