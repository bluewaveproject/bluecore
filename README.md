# bluecore
A repository that has the packages for Blue Wave. If they aren't present anywhere else except the AUR or if they are modified.

NOTE: Packages may not always be up-to-date because it's being managed by one person. 

Well... If you want to add the repo on your current Linux system (only supports any distro that uses 'pacman' as a default package manager.), then add this line at the end of /etc/pacman.conf.

```
[bluecore]
SigLevel = Optional DatabaseOptional
Server = https://gitlab.com/bluewaveproject/$repo/-/raw/main/$arch
```
