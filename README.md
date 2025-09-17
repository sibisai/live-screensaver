# YouTube Screensaver

A simple static site that plays random YouTube walking tour playlists with a glass-style clock overlay.  
Supports different playlists by URL path (e.g. `/cars`, `/homes`) and single video playback at `/yt/<YouTube URL or ID>`.

## Features

- Random start time for each session.
- Continuous playback of a shuffled playlist.
- 12-hour clock overlay with translucent "glass" style.
- Path-based routing:
  - `/` → default playlist
  - `/cars` → cars playlist
  - `/homes` → homes playlist
  - `/yt/<YouTube URL or ID>` → play a specific video

## Run Locally

You just need a static file server. Examples:

### Python

```bash
# In repo root
npx serve -s
```
