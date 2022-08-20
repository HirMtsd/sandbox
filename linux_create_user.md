# Ubuntu
# 1999とuseridと"User Name"を変更
``` user_add.sh
sudo useradd -u 1999 -g 1000 -m -s /usr/bin/bash -c "User Name" userid
sudo usermod -aG adm,cdrom,sudo,dip,plugdev,lpadmin,lxd,sambashare userid
sudo passwd userid
```


# Kali
# 1999とuseridと"User Name"を変更
``` user_add.sh
sudo useradd -u 1999 -g 1000 -m -s /usr/bin/bash -c "User Name" userid
sudo usermod -aG developer,dialout,cdrom,floppy,sudo,avdio,dip,video,plugdev,netdev,bluetooth userid
sudo usermod -aG wireshark,scanner,kaboxer userid
sudo passwd userid
```


# Rocky
# 1999とuseridと"User Name"を変更
``` user_add.sh
sudo useradd -u 1999 -g 1000 -m -s /usr/bin/bash -c "User Name" userid
sudo usermod -aG wheel userid
sudo passwd userid
```
