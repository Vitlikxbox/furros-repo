# FurrOS package repository 🐾

Pacman repository with the packages made by the FurrOS project: branding, themes, wallpapers,
Lapa's School, `furros-drivers` and a few prebuilt AUR packages FurrOS ships.

The packages live in the [`x86_64` release](../../releases/tag/x86_64) of this repository.
FurrOS installs and configures the repository for you. To add it to an existing system by hand:

```ini
# /etc/pacman.conf
[furros]
Server = https://github.com/Vitlikxbox/furros-repo/releases/download/$arch
```

Packages and the database are signed with the FurrOS key (installed by `furros-keyring`).

Main project: [Vitlikxbox/FurrOS](https://github.com/Vitlikxbox/FurrOS) · [furros.xyz](https://furros.xyz/)

**Good dogs only. 🐾**
