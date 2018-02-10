# dotfiles

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
packer -S  ttf-roboto-mono paper-icon-theme-git  pi-bluetooth 
```

```
systemctl enable bluetooth brcm43438 NetworkManager sddm
```

```
sudo reboot 
```
