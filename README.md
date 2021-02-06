# If Nandu's Machine

## Setup RTMP

Start RTMP server with `docker-compose up -d`.
Monitor status with `docker-compose logs -f`

## OBS

### Streaming Settings
Set livestream server to `rtmp://localhost/obs`
Set stream key to `test`

### OBS Zoom Source
Add a new playlist item with `rtmp://zoom.yadunut.com/zoom/test`.
This will add the zoom call as a source

## Zoom Settings
stream URL: `rtmp://zoom.yadunut.com/zoom`
stream Key: `test`
Livestream URL: `https://youtube.com/`

# If Backup Machine

## Setup RTMP

Start RTMP server with `docker-compose up -d`.
Monitor status with `docker-compose logs -f`

## OBS

### Streaming Settings
Set livestream server to `rtmp://CloudSeverIP/obs`
Set stream key to `test`

### OBS Zoom Source
Add a new playlist item with `rtmp://CloudServerIP/zoom/test`.
This will add the zoom call as a source

## Zoom Settings
stream URL: `rtmp://CloudServerIP/zoom`
stream Key: `test`
Livestream URL: `https://youtube.com/`
