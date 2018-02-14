# dotfiles

for archlinux:

```
cp -a config ~/.config
```

```
sudo mkdir -p /usr/share/wallpapers &&
sudo curl https://img2.goodfon.com/original/2048x1820/3/b6/android-5-0-lollipop-material-5355.jpg --output /usr/share/wallpapers/android-5-0-lollipop-material-5355.jpg
```

```
sudo pacman -S packer git base-devel xorg-server xf86-video-fbdev xorg-xrefresh xfce4 xfce4-goodies xarchiver gvfs gvfs-smb sshfs sddm ttf-roboto arc-gtk-theme blueman pulseaudio-bluetooth pavucontrol networkmanager network-manager-applet gnome-keyring
```

```
packer -S ttf-roboto-mono paper-icon-theme-git pi-bluetooth 
```

```
systemctl enable bluetooth brcm43438 NetworkManager sddm
```

```
sudo reboot 
```

for alpine:

```
cp -a alpine-config ~/.config
```

```
sudo mkdir -p /usr/share/wallpapers &&
sudo curl https://img2.goodfon.com/original/2048x1820/3/b6/android-5-0-lollipop-material-5355.jpg --output /usr/share/wallpapers/android-5-0-lollipop-material-5355.jpg
```

```
sudo sh -c 'echo "@testing http://dl-cdn.alpinelinux.org/alpine/edge/testing" >> /etc/apk/repositories'
```

```
sudo setup-xorg-base
```

```
sudo apk --update --no-cache add xf86-video-fbdev xf86-input-mouse xf86-input-keyboard xfce4 xfce4-mixer xfce4-wavelan-plugin lxdm paper-icon-theme arc-theme@testing gvfs gvfs-smb sshfs wpa_supplicant networkmanager network-manager-applet@testing gnome-keyring
```

```
sudo rc-update add wpa_supplicant boot
```

```
sudo rc-update add dbus lxdm networkmanager
```

```
sudo sh -c 'echo b43 >> /etc/modules'
```

```
sudo sh -c 'echo "managed=true

[ifupdown]
managed=true" >> /etc/NetworkManager/NetworkManager.conf'
```

```
sudo reboot
```

```
sudo setup-interface 
```

> setup `wlan0`
