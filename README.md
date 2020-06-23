# Plex Server On Docker for architecture AMD64
Plex Server with Flexget, Transmission and Subliminal (for subtitles). Everything in Docker.

It's necessary to install [Docker](https://docs.docker.com/engine/install/) and [Docker-Compose](https://docs.docker.com/compose/install/). It works on Windows, OS X and Linux.

## How to start:

Edit `.env` and put your locations for Transmission (torrents), Flexget (movies and series), user-pass for Opensubtitles and hostname for Plex.
And then run:

```
docker-compose up -d
```

## Credits:

From the repository of Pablo Fredrikson (pablokbs/plex-rpi). I changed the architecture to AMD64 and i added Subliminal for subtitles.
