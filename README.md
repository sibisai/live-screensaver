# YouTube Screensaver

A simple static site that plays random YouTube playlists with a glass-style clock overlay and an Apple-style tab switcher.  
Supports different playlists by URL path or by passing a custom YouTube video.

## Features

- Random start time for each session.
- Continuous playback of a shuffled playlist.
- 12-hour clock overlay with translucent "glass" style.
- Overlay tabs to switch between categories (Walk, Home, Drive).
- Path and query-based routing:
  - `/` → Walk playlist (default)
  - `/home` → Home playlist
  - `/drive` → Drive playlist
  - `?yt=<YouTube URL or ID>` → play a specific video
  - `#yt=<YouTube URL or ID>` → play a specific video

## Run Locally

Use a static server that supports single-page apps:

```bash
# From repo root
npx serve -s .
```
