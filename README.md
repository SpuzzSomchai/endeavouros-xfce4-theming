# Still in progress to port for Debian/Ubuntu 

## endeavouros-xfce4-theming
[![Maintenance](https://img.shields.io/maintenance/yes/2023.svg)](https://github.com/endeavouros-team)

![XFCE4 Screenshot](https://raw.githubusercontent.com/endeavouros-team/screenshots/master/endeavouros-xfce4-apollo.png "XFCE4 Screenshot")
The EndeavourOS XFCE4 Theming.

## Need To Edit Scripts
It's in progress. I need to finish looking at the code and checking packages. Feel free to fork. I am just a hack and not a programmer. 
I was a trained network engineer. Then I went into management. Management paid better. Now I am retired. Go me. 

All credit to EndeavourOS crew. They did the heavy lifting. I'm just mucking about. 

## Installing the theme:

### Manually
`git clone https://github.com/endeavouros-team/endeavouros-xfce4-theming`

`cd endeavouros-xfce4-theming`

`rm -rf ~/.config/Thunar ~/.config/qt5ct ~/.config/xfce4 ~/.cache`

`cp .Xresources ~/.Xresources`

`cp -R .config/ ~/`

`dbus-launch dconf load / < xed.dconf`

`sudo systemctl reboot`
### Via the Script
or if you are really lazy use the script:

`wget https://raw.githubusercontent.com/endeavouros-team/endeavouros-xfce4-theming/master/xfce.sh`

`sh ./xfce.sh`

