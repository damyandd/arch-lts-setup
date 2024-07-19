## About
This repository tracks my **UNOFFICIAL** Arch Linux LTS branch setup for a minimal GNOME 46 system. The output of `pacman -Qqen` is [pkglist.txt](pkglist.txt). Pacman mirror server is set to a snapshot from [Arch Linux Archive](https://wiki.archlinux.org/title/Arch_Linux_Archive) and packages are rebuilt when security updates are available. The current used snapshot is from 2024-06-17. [AUR](https://aur.archlinux.org/) usage is mostly for packages containing prebuilt binary applications like Google Chrome, Firefox, LibreOffice, Visual Studio Code, Zoom and Viber.
### Changelog
#### 2024-07-19
Updates:
- qt5-base 5.15.14+kde+r143-1
- libndp 1.9-1
#### 2024-07-18
Updates:
- gtk3 1:3.24.43-1
- krb5 1.21.3-1
- exiv2 0.28.3-1
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
