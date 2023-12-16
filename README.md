# Gnome-setup

install most apps:
```
sudp apt install kitty thunar xfce4-settings neofetch zsh ranger python3-pil git curl conky neofetch -y
```
## Apply theme for Other shell Apps
To apply theme for other Gnome apps, just copy files from (```~/.themes/[theme-name]/gtk-4.0```) to (```~/.config/gtk-4.0```) then reboot.


## Force kitty to use Gnome theme
add to ktty.conf:
```
linux_display_server x11
```
