# sonarr-tak

## Snap Description
Canonical Snap for Sonarr Release 4+\
https://snapcraft.io/sonarr-tak

## Sonarr Description
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
Core20 is still required for Sonarr dependencies\
You must Backup and Restore your configuration for transition from v3 to v4\
Update All Series to get back Series covers...\
Service is restarted on any condition.

Post install commands required to access media folders and see resources :
```
sudo snap connect sonarr-tak:removable-media
sudo snap connect sonarr-tak:mount-observe
```
