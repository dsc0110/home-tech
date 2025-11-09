# Home Tech

## raspberry
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

## ananas
```
mkdir -p {REPODIR}/ananas/appdata/{radarr,sonarr,bazarr,prowlarr,plex,transmission}
mkdir -p {REPODIR}/ananas/data/{torrents/{shows,movies,music},media/{shows,movies,music}}
```

## Todo
 - rsync nas
 - traeffik
 - nextcloud
 - servarr