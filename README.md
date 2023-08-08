# proxmox-dev
Development workstation setup on Proxmox.
 - use for testing and configuration
 - ansible, git, xfce desktop environment, xRDP

## Install Proxmox on the workstation
Perform a "baremetal" install using the Proxmox iso downloaded from proxmox.  (I use ventoy, but a DVDrom or iso burned to USB will work)

## Run initialization script
Run this command to download and run the playbook
```
wget -O - https://raw.githubusercontent.com/vichanzo/proxmox-dev/main/test.sh | bash
```
