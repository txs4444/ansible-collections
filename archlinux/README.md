# Ansible Collections - Archlinux
This is collection of miscellaneous roles for Arch Linux.

## Roles
List of roles:
* base_packages - ensures some basic package are installed, so you can edit text base file, and read manuals (base-devel, man-db, man-pages, text-info, vim)
* enable_aur - makes it easy to install AUR packages using ansible, dependes on [kewlfft.aur](https://github.com/kewlfft/ansible-aur); installs [yay](https://github.com/Jguer/yay) (aur helper) and configure user which is used to install AUR packages
* upgrade_system - uses pacman to upgrade system
* tensorflow - prepares environment to play with Tensorflow; adds user, installs miniconda, and setup conda env (named: tensor_env) with tensorflow, python 3.8, matplotlib
