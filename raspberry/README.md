# raspberry

```
mkdir -p {REPODIR}/raspberry/appdata/{pihole,home-assistant}

vim /etc/fstab
UUID={UUID}       {REPODIR}/raspberry/data    ext4    defaults        0       2

vim /etc/samba/smb.conf
[data]
path = {REPODIR}/raspberry/data
writeable = yes
browseable = yes
public = yes
```

## pihole
-   internet/account info: use other dns servers
-   dhcp/set as local dns server
-   update block list

## home-assistant
todo: backup dashboards

## Todo
-   traeffik
-   nextcloud
-   rsync nas
-   navidrome
-   webapp