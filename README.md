# stanford-hackathon-media

Video hosting for a portfolio PDF. Two MP4 files served over GitHub Pages.

| File | Duration | Size |
| --- | --- | --- |
| `video_01.mp4` | 44.6 s | 3,776,484 B |
| `video_02.mp4` | 33.6 s | 2,826,597 B |

`index.html` is a dependency-free player page: `controls`, `playsinline`,
Chinese titles, no CDN, no external fonts, no JavaScript.

Both files are H.264 High / yuv420p + AAC-LC at 432x768, 30 fps — the most
broadly compatible mobile profile. Range requests are enabled, so a browser
can seek without downloading the whole file.
