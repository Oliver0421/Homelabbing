# Homelabbing


### Make your old computer useful

#### Install Proxmox


#### Go to [Proxmox virtual-environment](https://www.proxmox.com/en/downloads/proxmox-virtual-environment) and download the ISO file

#### Flash the firmware on a usb stick with ex [BalenaEtcher](https://etcher.balena.io/). 

1. When you are inside the Boot menu choose your target harddisk.
   
2. Next step is where it is located, Choose your country and key layout

3. Set email user and password

4. Hostname, name it whatever you want
   - Give it an IP Address that is not taken yet by the router
   -  Type in the IP Address for the Gateway
   - DNS Server, can be same as Gateway

5. Confirm and install. Unplugg the bootable usb stick, when rebooting



### Nice, Now you have a fresh install of Proxmox on your computer

#### You need to connect your computer with Ethernet if you havent done so. 

##### Then type in your `https://(assigned-ip-address):8006/` where assigened ip address, what you gave it, like 0.0.0.10 at the end, port 8006 

##### Accept the risk, first time you need to login

##### User: Root

##### Password: Your password

![Proxmox-console](src/)

###### Now you are inside the console for proxmox

### Change to no-subscription

#### Visit this site  [Community-scripts](https://community-scripts.github.io/ProxmoxVE/scripts?id=post-pve-install). To get a runnable script file for updating the system. 

![Proxmox-console](src/)

### Go to shell, on your named server, paste it


![Proxmox-console](src/)

##### Here you can change settings. 

