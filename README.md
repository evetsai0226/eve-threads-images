# eve-threads-images

Public image hosting for Eve's Threads scheduled posts via [eve-threads-scheduler](https://github.com/evetsai0226/eve-threads-scheduler).

## URL Pattern

```
https://raw.githubusercontent.com/evetsai0226/eve-threads-images/main/images/{post-id}.jpg
```

## File Naming

- Single image: `{post-id}.jpg`  →  e.g. `2026-05-18-001.jpg`
- Multi-image carousel: `{post-id}-01.jpg`, `{post-id}-02.jpg`, ...

## Spec

- Format: JPEG / PNG / GIF
- Size: ≤ 8MB (Threads API limit)
- Aspect ratio: within Threads default range

## Why public?

Threads API (`media_type=IMAGE` / `CAROUSEL`) requires a publicly accessible HTTPS URL to fetch the image. This repo only hosts cover images that will be published to Threads anyway — no private content.
