# 图形界面安装

### 首先安装xorg

` pacman -S xorg-server xorg-xinit `

### 显卡驱动（由于是虚拟机）

` pacman -S xf86-video-vesa `

> 此次为第二次启动，安装是仍出现无法联网的情况

输入` dhcpcd ` 使其联网

### gnome 

` pacman -S gnome gnome-extra `

` pacman -S gnome gdm `

` systemctl enable gdm `

***出现的问题***

当` systemctl enable gdm `时

出现

> Failed to enable unit: Unit gdm.service does not exist


