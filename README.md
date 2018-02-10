# dotfiles

```
cp -a config ~/.config
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
