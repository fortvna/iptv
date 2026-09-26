# Dedup

Exact-name dedupe applied 2026-09-26.

- Source list: 2057 channels (GitHub `playlist.m3u` from 2026-09-19)
- Key: `tvg-language` + case-insensitive display name
- Kept: first occurrence
- Result: **1758** unique channels (dropped **299** extra copies)
- Mix: English 1240 · Spanish 437 · French 81

The previous commit only added this note and did not replace `playlist.m3u`.
This update publishes the cleaned list.
