# Ansible Collections
This repository contains different collections I created for myself to use with VMs or to configure my OS.
In case someone can find them useful I put them here and documented them for others and my future self.

# Collections
List of collections:
* [txs4444.archlinux](archlinux/README.md) - miscellaneous roles for Arch Linux
* [txs4444.generic](generic/README.md) - miscellaneous roles for Linux with no particular distribution in mind

# Usage
## Installation
As of now, collections are not available through ansible-galaxy and have to be installed manualy in order to use.
1) To do this you need to clone this repository
```
git clone git@github.com:txs4444/ansible-collections.git
```
2) Enter directory of the collection you want to install, e.g. archlinux
3) Build collection - after this command you should have `txs4444-archlinux-0.0.1.tar.gz` file in directory.
```
ansible-galaxy collection build
```
4) Install collection
```
ansible-galaxy collection install txs4444-archlinux-0.0.1.tar.gz
```
