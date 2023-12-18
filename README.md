# Gnome-setup

install most apps:
```
sudo apt install kitty thunar xfce4-settings neofetch zsh ranger python3-pil git curl conky neofetch -y
```
## Apply theme for Other shell Apps
To apply theme for other Gnome apps, just copy files from (```~/.themes/[theme-name]/gtk-4.0```) to (```~/.config/gtk-4.0```) then reboot.


## Force kitty to use Gnome theme
add to ktty.conf:
```
linux_display_server x11
```

Install eza:
```
sudo mkdir -p /etc/apt/keyrings
wget -qO- https://raw.githubusercontent.com/eza-community/eza/main/deb.asc | sudo gpg --dearmor -o /etc/apt/keyrings/gierens.gpg
echo "deb [signed-by=/etc/apt/keyrings/gierens.gpg] http://deb.gierens.de stable main" | sudo tee /etc/apt/sources.list.d/gierens.list
sudo chmod 644 /etc/apt/keyrings/gierens.gpg /etc/apt/sources.list.d/gierens.list
sudo apt update
sudo apt install -y eza
```
