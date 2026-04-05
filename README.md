-----------------------------

# Start The Installation:

Before you started, get these pakages:

Arch:
`sudo pacman -S feh i3 xfce4-palne`

Debian:
`sudo apt install feh i3 xfce4-palne`

Fedora:
`sudo dnf install i3 i3status dmenu i3lock xbacklight feh conky xfce4-palne`

(ONLY FOR LINUX USERS)

(whatever you distro on, like Arch, Debian, and Fedora)

# Non-Manual:

Get `install.sh` from [release](https://github.com/kk2lly/hinnkaDE-i3-WM/releases/tag/Shell)

-----------------------------

# Manual:

1: Open the terminal and type: 

`git clone https://github.com/kk2lly/hinnkaDE-i3-WM`

`git clone https://github.com/HinnkaStudios-Open-Sources-Project/hinnkaDE-i3-WM`

Once done, type `cd hinnkaDE-i3-WM`




2: Make `hinnkaDE-i3` folder on `/usr/local/bin` like this:

`sudo mkdir /usr/local/bin/hinnkaDE-i3`

Copy the bash script to: `/usr/local/bin/hinnkaDE-i3`

`sudo cp hinnkaDE.sh /usr/local/bin/hinnkaDE-i3`

Make shell file executable:

`sudo chmod +x /usr/local/bin/hinnkaDE-i3/hinnkaDE.sh`

Copy the wallpaper image to: `/usr/local/bin/hinnkaDE-i3`

`sudo cp Wallpaper.png /usr/local/bin/hinnkaDE-i3`




3: Copy the desktop session file must be to `/usr/share/xsessions`

Before doing that, create `xsessions` like this:

`sudo mkdir /usr/share/xsessions`

Then, type copy the desktop session file:

`sudo cp hinnkaDE-i3.desktop /usr/share/xsessions/`




4: Once done, log out to change desktop session to ''hinnkaDE i3'' and log back on and done!

NOTE: If you forgot to do `sudo chmod +x /usr/local/bin/hinnkaDE-i3/hinnkaDE.sh` or installing `i3` and `xfce4-palne`, it may not working

-----------------------------
