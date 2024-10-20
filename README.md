# sonarr-tak

[![sonarr-tak](https://snapcraft.io/sonarr-tak/badge.svg)](https://snapcraft.io/sonarr-tak)
![snap arch](https://badgen.net/snapcraft/architecture/sonarr-tak)
![snap size](https://badgen.net/snapcraft/size/sonarr-tak/amd64/stable)

## Snap Description
Canonical Snap for Sonarr Release 4+\
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

Sonarr Release 4+\
Mono is no more required (you can now use HTTPS certificate)\
Core20 is still required for dependencies\
You must Backup and Restore your configuration for transition from v3 to v4\
Update All Series to get back Series covers...\
Service is restarted on any condition.

Post install commands required to access media folders and see resources :
```
sudo snap connect sonarr-tak:removable-media
sudo snap connect sonarr-tak:mount-observe
```

Post install commands required to access home folder :
```
sudo snap connect readarr-tak:home
```
**!!! Files can only be written in a directory owned by 'root' !!!**\
This is due to current behavior and restrictions of snaps running as daemon by Canonical.

## FAQ
See my common doc about [FAQ](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#FAQ).

## Building
The snap requires Core20 for .NET source dependencies.\
See my common doc about [building a snap](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Building).
## Versionning
See my common doc about [versionning](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Versionning).
