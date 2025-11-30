# youtube-downloader

This repo contains a docker-compose file for running pinchflat.

Pinchflat is a service built on top of yt-dlp which provides some pre-contiguration and a gui to configure which streams to download from.

The compose file contains basic configuration with an expected $CONFIG_BASE and $CONTENT_BASE to be provided from an .env file.