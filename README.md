# netspeed_install
netspeed install in ubuntu 22.04
```
sudo apt install gettext make 
  cd /tmp/
    git clone https://github.com/hedayaty/NetSpeed.git
    cd NetSpeed/
  757  make install 
  758  cp -r locale/en_CA/ locale/nl_NL
  759  make install
  760  sudo cp -r ~/.local/share/gnome-shell/extensions/netspeed@hedayaty.gmail.com /usr/share/gnome-shell/extensions/
  762  reboot
now enable netspeed in gnome-extansions manager
```
