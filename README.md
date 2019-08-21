# hosts-switcher
A lightweight hosts management script by switch or merge hosts files to /etc/hosts
## Initialize 
- create a folder to manage hosts files
- put the hosts-switcher into the folder
- chmod +x hosts-swicher
## Usage
create hosts files in the hosts management folder created above
- switch single hostFile
```
sudo ./hosts-swicher hostsFile1
```
- merge multipule hostsFiles
```
sudo ./hosts-swicher hostsFile1 hostsFile2 [hostsFile3...]
```
