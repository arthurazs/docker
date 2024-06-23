# arr

**IMPORTANT** Update the values in `.env`.

## Prowlarr (Indexer)

Remember that the IP to each server is the server's hostname, i.e., radarr.

- Add the indexers: 1337x, Badass Torrents, BitSearch
- Settings > Apps
    - Radarr
    - Lidarr
    - Sonarr
- Settings > General > Security > Authentication > Forms (Login Page)
- Settings > General > Analytics > Disable: Send Anonymous Usage Data

## Radarr (Movies)

- Settings > Media Management > Add Root Folder > /data/media/movies
- Settings > Download Clients > Torrents > Transmission > Category > radarr
- Settings > General > Security > Authentication > Forms (Login Page)
- Settings > General > Analytics > Disable: Send Anonymous Usage Data

## Sonarr (Shows)

- Settings > Media Management > Add Root Folder > /data/media/shows
- Settings > Download Clients > Torrents > Transmission > Category > sonarr
- Settings > General > Security > Authentication > Forms (Login Page)
- Settings > General > Analytics > Disable: Send Anonymous Usage Data

## Lidarr (Music)

- Settings > Media Management > Root Folders > /data/media/music
- Settings > Download Clients > Torrents > Transmission > Category > lidarr
- Settings > General > Security > Authentication > Forms (Login Page)
- Settings > General > Analytics > Disable: Send Anonymous Usage Data

## Bazarr

- Settings > General > Security > Authentication > Form
- Settings > General > Analytics > Disable
- Settings > Languages
    - Languages Filter: Brazilian Portuguese, English
    - Embedded Tracks Language: English
    - Languages Profile: PB, EN
    - Default Settings: Enable Series, Movies
- Providers > OpenSubtitles.com
- Sonarr > Enable Use Sonarr
- Radarr > Enable Use Radarr

## Jellyfin

- Check steps next time I setup this stack

## Jellyseerr

- Check steps next time I setup this stack
