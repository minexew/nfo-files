Download commmand

    yt-dlp -S "height:1080" -o "E%(playlist_index)s.%(ext)s" --write-info-json \
            "https://www.youtube.com/playlist?list=PLR7yrLMHm11X6-M_usCj5H-gdstyWNLXQ"

- 4k files are unreasonably massive, recommended to stick to 1080p
- We omit the episode title because it seems to trip up Jellyfin and prevent correct detection of the NFO file
