# ananas

```
mkdir -p {REPODIR}/ananas/appdata/{radarr,sonarr,bazarr,prowlarr,plex,transmission}
mkdir -p {REPODIR}/ananas/data/{torrents/{shows,movies,music},media/{shows,movies,music}}
```

## jellyfin

### Transcoding
Hardcare acceleration: Intel QuickSync (QSV) <br>
Enable hardware decoding for:<br>
-   H264 
-   HEVC
-   MPEG2
-   VC1
-   VP8
-   VP9
-   HEVC 10bit
-   HEVC RExt 8/10bit
-   HEVC RExt 12bit

## transmission
set default download folder: /media/torrents

## prowlarr
download client: transmission
applications: add radarr (api key from radar)
applications: add sonarr (api key from sondar)

## radarr
download client: transmission

## sonarr
download client: transmission
