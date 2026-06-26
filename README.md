# sonarr-tak

[![sonarr-tak](https://snapcraft.io/sonarr-tak/badge.svg)](https://snapcraft.io/sonarr-tak)
![snap arch](https://badgen.net/snapcraft/architecture/sonarr-tak)
![snap size](https://badgen.net/snapcraft/size/sonarr-tak/amd64/stable)

## Snap Description
Canonical Snap for Sonarr\
https://snapcraft.io/sonarr-tak

## Sonarr Description
<img src="/icon.svg" width="100">
Sonarr is a PVR for Usenet and BitTorrent users.\
It can monitor multiple RSS feeds for new episodes of your favorite shows
and will grab, sort and rename them. It can also be configured
to automatically upgrade the quality of files already downloaded
when a better quality format becomes available.

See https://sonarr.tv for more details.

## Information
The web interface is accessible by default at http://localhost:8989

Sonarr Release\
Service is restarted on any condition.

Post install commands required to access media folders and see resources :
```
sudo snap connect sonarr-tak:removable-media
sudo snap connect sonarr-tak:mount-observe
```

**!!! Files can only be written in a directory owned by 'root' !!!**\
**!!! Home base directory content is not readable !!!**

This is due to current behavior and restrictions of snaps by Canonical.\
Check common doc in FAQ if you want to setup data in /home directory.

## FAQ
See common doc about [FAQ](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#FAQ).

## Building
See common doc about [building a snap](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Building).
## Versionning
See common doc about [versionning](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Versionning).
