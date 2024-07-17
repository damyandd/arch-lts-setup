## About
This repository contains **UNOFFICIAL** Arch Linux LTS setup for a minimal GNOME 46 system. The output of `pacman -Qqen` is [pkglist.txt](pkglist.txt). Pacman mirror server is set to a snapshot from [Arch Linux Archive](https://wiki.archlinux.org/title/Arch_Linux_Archive) and packages are rebuilt when security updates are available. [AUR](https://aur.archlinux.org/) usage is mostly for binary applications like Google Chrome, Firefox, LibreOffice, Visual Studio Code, Zoom and Viber.
### Changelog
#### 2024-07-17
Updates:
- linux-lts 6.6.40-1
- ca-certificates 20240618-1
- ca-certificates-utils 20240618-1
- ca-certificates-mozilla 3.102-1
- nss 3.102-1
- openssh 9.8p1-1
#### 2024-06-17
Pacman mirror server is set to
```
Server = https://archive.archlinux.org/repos/2024/06/17/$repo/os/$arch
```
