# hosts-switcher
A lightweight hosts management script by switch or merge hosts files to /etc/hosts
## Initialize 
- create a folder to manage hosts files
- put the hosts-switcher.sh into the folder
- chmod +x hosts-swicher.sh
## Usage
- switch single hostFile
```
sudo ./hosts-swicher.sh hostsFile1
```
- merge multipule hostsFiles
```
sudo ./hosts-swicher.sh hostsFile1 hostsFile2 [hostsFile3...]
```
