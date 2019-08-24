# hosts-switcher
A lightweight hosts management script by switch or merge hosts files to **/etc/hosts**
## Initialize 
- create a folder to manage hosts files
- put the hosts-switcher into the folder
- chmod +x hosts-swicher
## Usage
1. create hosts files in the hosts management folder created above.
2. apply hosts files
- switch single hosts file to **/etc/hosts**
```
sudo ./hosts-swicher hostsFile1
```
- merge multipule hosts files to **/etc/hosts**
```
sudo ./hosts-swicher hostsFile1 hostsFile2 [hostsFile3...]
```
3. the currently applied hosts files will be recorded in the host-switcher.log file.