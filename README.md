# iptv

Public merged playlist of **English, Spanish, and French** channels that actually play.

## Use this list

Paste this URL into VLC, TiviMate, IPTV Smarters, or any player that accepts M3U:

```
https://raw.githubusercontent.com/fortvna/iptv/main/playlist.m3u
```

[playlist.m3u](./playlist.m3u) is the file itself.

## What is in it

- English, Spanish, and French only
- Streams probed for real HLS / MPEG-TS content
- Dead streams dropped
- A previously-good stream is held one extra cycle if it fails once
- Exact-name duplicates removed (same language + same name, case-insensitive); first copy kept

Updated by the On Air merger whenever you click **Rebuild playlist**.
