

# Arch linux Ultimate Install

Install and configure arch linux


## Prerequisites

- A working internet connection
- Logged in as 'root'
- generous amounts of patience

## How to get it
### With git
- Get list of packages and install git: `pacman -Sy git`
- get the script: `git clone git://github.com/pasiegel/aui`

### Without git
- get the script: ` wget https://github.com/pasiegel/aui/tarball/master -O - | tar xz`

## How to use
- FIFO [system base]: `cd <dir> && ./fifo`
- LILO [the rest...]: `cd <dir> && ./lilo`

## FIFO SCRIPT
- Configure keymap
- Select editor
- Automatic configure mirrorlist
- Create partition
- Format device
- Install system base
- Configure fstab
- Configure hostname
- Configure timezone
- Configure hardware clock
- Configure locale
- Configure mkinitcpio
- Install/Configure bootloader
- Configure mirrorlist
- Configure root password

## LILO SCRIPT
- Backup all modified files
- Install additional repositories
- Create and configure new user
- Install and configure sudo
- Automatic enable services in systemd
- Install an AUR Helper [yaourt, packer, pacaur]
- Install systemd
- Install Preload
- Install Xorg
- Install GPU Drivers
- Install CUPS
- Install Additional wireless/bluetooth firmwares
- Install DE or WM [Cinnamon, Enlightenment, FluxBox, GNOME, i3, KDE, LXDE, OpenBox, XFCE]
- Install Developement tools [Vim, Emacs, Eclipse...]
- Install Office apps [LibreOffice, GNOME-Office, Latex...]
- Install System tools [Wine, Virtualbox, Grsync, Htop]
- Install Graphics apps [Inkscape, Gimp, Blender, MComix]
- Install Internet apps [Firefox, Google-Chrome, Jdownloader...]
- Install Multimedia apps [Rhythmbox, Clementine, Codecs...]
- Install Fonts [Liberation, MS-Fonts, Google-webfonts...]
- Install and configure Web Servers
