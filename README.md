# proxmox-dev
Development workstation setup on Proxmox.
 - use for testing and configuration
 - ansible, git, xfce desktop environment, xRDP

## Install Proxmox on the workstation
Perform a "baremetal" install using the Proxmox iso downloaded from proxmox.  (I use ventoy, but a DVDrom or iso burned to USB will work)

## Run initialization script
Run this command as root (or add sudo) to download and run the initialization script.
This script will install git and ansible and clone the repoository to your computer.
```
wget -O - https://raw.githubusercontent.com/vichanzo/proxmox-dev/main/initialize.sh | bash
```

## Run the Ansible Playbook locally.
This playbook will install xfce, xRDP
```
ansible-playbook local.yml
```
