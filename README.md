# Learn-OpenWrt
OpenWrt Basic knowledge

Openwrt 系统刷机，或者在线升级后。进入ssh执行：
1. firstboot -y && reboot now
或者：
2. umount /overlay && jffs2reset && reboot now
