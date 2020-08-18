# Sekhmet
Kali's lightweight sister - a work in progress as I decide what I want to have on it

# Installation
Install bare bones Kali from ISO  
- https://www.kali.org/downloads/  

Change root password  
- sudo su; passwd root  
  
On VBox - run Guest Additions  
- bash ./VBoxLinuxAdditions.run  
  
On VMWare - install and run VMWare Tools  
- apt install -y --reinstall open-vm-tools-desktop fuse  
- reboot -f  
  
Create shared folder with host in hypervisor  
- On VMWare - see https://www.kali.org/docs/virtualization/install-vmware-tools-kali-guest/  
- To mount the shared folder run -> mount-shared-folders  
  
Modify the Sekhmet script with your passphrase in place of ****** for SSH keygen  
Copy the Sekhmet script file to root, chmod +x, and run  
