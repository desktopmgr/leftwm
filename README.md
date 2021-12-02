## leftwm  
  
A tiling window manager based on binary space partitioning  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/desktopmgr/leftwm/raw/main/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install leftwm libnotify-bin catfish slimlock acpi-support wireless-tools gtk2-engine-murrine xfce4-terminal firefox xfce4-power-manager volumeicon-alsa xscreensaver policykit-1-gnome gnome-settings-daemon network-manager-gnome conky polybar xbindkeys tint2
```  

Fedora Based:

```shell
yum install xfce4-power-manager gtk2-murrine-engine acpid wireless-tools xfce4-terminalfirefox  volumeicon xscreensaver policykit-1-gnome gnome-settings-daemon network-manager-gnome polybar xbindkeys tint2
```  

Arch Based:

```shell
pacman -S leftwm gtk-engine-murrine xfce4-power-manager acpi wireless-tools xfce4-terminal firefox volumeicon xscreensaver polkit-gnome gnome-settings-daemon network-manager-applet conky tint2 xbindkeys polybar
```  

MacOS:  

```shell
brew install
```
  
```shell
mv -fv "$HOME/.config/leftwm" "$HOME/.config/leftwm.bak"
git clone https://github.com/desktopmgr/leftwm "$HOME/.config/leftwm"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/leftwm" target="_blank" rel="noopener noreferrer">leftwm wiki</a>  |  
  <a href="https://github.com/baskerville/leftwm" target="_blank" rel="noopener noreferrer">leftwm site</a>
</p>  
