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
update block list

## home-assistant
todo: backup dashboards

## Todo
-   rsync nas
-   traeffik
-   nextcloud
-   webapp
