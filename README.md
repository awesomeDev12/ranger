# Ranger


To use my config file
```
git clone https://github.com/awesomeDev12/ranger.git ~/.config/ranger
```

To copy defaults
```
ranger --copy-config=all
```

To add VLC flatpak 
```
mime ^video|audio, has org.videolan.VLC,      X, flag f = org.videolan.VLC -- "$@"
```

## For image support install w3m (Tested on my alacritty)

Install w3m on Arch-Linux
```
pacman -sS w3m
sudo pacman -S w3m
```

Install w3m on Ubuntu
```
apt search w3m
sudo apt install w3m
```

## Install Ranger

Install ranger on Arch-Linux
```
pacman -sS ranger
sudo pacman -S ranger
```

Install ranger on Ubuntu
```
apt search ranger
sudo apt install ranger
```
