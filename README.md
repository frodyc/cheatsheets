# Cheat Sheets

## Arch setup

The aim of this cheat sheet is to speed up Arch installations. The idea is to use tmux to copy and paste several commands at a time (you could also make the file a script). If you know what you are doing, this should also reduce the risk of making mistakes (typo, forgetting a command).

I would advise against running any of these commands if you don't know what they do. You should at least have read the following wiki articles before doing part 1:

https://wiki.archlinux.org/index.php/installation_guide

https://wiki.archlinux.org/index.php/Dm-crypt/Encrypting_an_entire_system#LVM_on_LUKS

https://wiki.archlinux.org/index.php/systemd-boot

Things this cheat sheet covers:

- UEFI
- Use of systemd-boot
- Full multi drive encryption (except for /boot) LVM on LUKS
- X11 with xinit

Things this cheat sheet does not cover:

- Secure boot
- Dual boot
- Desktop environments
