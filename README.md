
* jellyfin x sonarr x radarr https://agatsyasingh.wordpress.com/2022/04/21/setting-up-a-media-server-with-docker-jellyfin-deluge-sonarr-and-radarr/
*


1. deluge default user is the web ui user, in config/web.conf.
2. the localconnection or other users in config/auth has no bearing on radaar,
   sonar etc
3. All services in the compose file need to be on the same bridged network to
   see each other
4. service configurations, via their respective web ui's, should use the
   service name
5. to configure overseerr without plex you first need to use a free plex acount
   to sign in and add the local user
