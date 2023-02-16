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
