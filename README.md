# WebDev VM container set up

An Ansible playbook for setting up xfce4 and i3 on base Arch VirtualBox.
Tested with [this image](https://sourceforge.net/projects/osboxes/files/v/vb/4-Ar---c-x/2022.01.01/CLI/64bit.7z/download)

## Description

Feels like home everytime

## Getting Started

### Notes

* To reuse the same image for >1 VM`s you need to make sure they have different UUID: 
```
VBoxManage internalcommands sethduuid /path/to/disk.vdi
```
* For SSH connection to VBox forward guest port 22 to any unused port at loopback(127.0.0.1)
* If you are getting PGP signature errors run 
```
pacman -Sy archlinux-keyring
```
* Install Python
* Run playbook
