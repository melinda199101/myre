# myre

### install node(node version v6.11.1)
```
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
sudo apt-get install -y nodejs
```
 
### vbox unlinked file system
add vbox install folder into system class path, then execute
```
VBoxManage setextradata ubuntu VBoxInternal2/SharedFoldersEnableSymlinksCreate/share 1
```
