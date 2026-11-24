# Everyday Frequency — reels

Finished 9:16 explainer reels for TikTok and Facebook, with their delivery details.
Files here are public so Metricool can fetch the video for scheduling.

## Layout
One folder per reel, named after the video file (its slug):

```
reels/<slug>/
  <slug>.mp4            final video, 1080×1920
  <slug>-cover.jpg      cover frame, 1080×1920
  <slug>.en-GB.srt      captions
  post.json             title, post text, network settings, public URLs, schedule
  DELIVERY.md           title, TikTok caption, Facebook description, SEO, pinned comment, assumptions
  FACTS.md              every claim with its source and date
  CREDITS               voice, music, fonts, map data and licences
```

Public video link pattern:
`https://raw.githubusercontent.com/cjavenue/everyday-frequency-reels/main/reels/<slug>/<slug>.mp4`
