# thaxas-lofi

A CDN mirror of [Open Lo-Fi](https://github.com/btahir/open-lofi) — 166
public-domain (CC0-1.0) lo-fi tracks — re-encoded to 96 kbps so they can be
streamed straight from a CDN.

Upstream ships the audio only as a single 554 MB release archive, so the files
cannot be addressed individually. This repository unpacks them, one file per
track, which lets them be served for free over jsDelivr:

```
https://cdn.jsdelivr.net/gh/MdShahnawazSheikh/thaxas-lofi@<commit>/audio/<filename>
```

Used by [Thaxas](https://thaxas.com) for its lo-fi study player.

## Licence

The audio is CC0-1.0 (public domain), exactly as released by Open Lo-Fi. All
credit for the music belongs to that project. `catalog.json` is reproduced from
upstream unchanged.

## Videos

`video/` holds 24 seamless loop videos (with stills in `video/thumbs/`) used by
Thaxas's immersive mode, served via jsDelivr. All are Pixabay content, free to
use under the [Pixabay Content License](https://pixabay.com/service/license-summary/).
All credit belongs to the original creators.

| File | Source |
|---|---|
| `alpine-hideout.mp4` | https://cdn.pixabay.com/video/2024/04/21/208812_large.mp4 |
| `blue-hour-fireplace.mp4` | https://cdn.pixabay.com/video/2024/03/15/204241-923909574_large.mp4 |
| `blue-rain.mp4` | https://cdn.pixabay.com/video/2019/10/24/28236-368501609_large.mp4 |
| `cabin-porch-snow.mp4` | https://cdn.pixabay.com/video/2024/12/02/244452_large.mp4 |
| `cat-by-the-fire.mp4` | https://cdn.pixabay.com/video/2024/12/11/246242_large.mp4 |
| `city-penthouse.mp4` | https://cdn.pixabay.com/video/2024/12/12/246433_large.mp4 |
| `crimson-evening.mp4` | https://cdn.pixabay.com/video/2025/02/17/258729_large.mp4 |
| `daydream.mp4` | https://cdn.pixabay.com/video/2025/12/19/323002_large.mp4 |
| `firepit-porch.mp4` | https://cdn.pixabay.com/video/2024/12/02/244362_large.mp4 |
| `golden-cabin.mp4` | https://cdn.pixabay.com/video/2024/04/15/208106_large.mp4 |
| `hilltop-sunset.mp4` | https://cdn.pixabay.com/video/2025/11/08/314688_large.mp4 |
| `lakeside-studio.mp4` | https://cdn.pixabay.com/video/2025/04/09/270983_large.mp4 |
| `midnight-windowsill.mp4` | https://cdn.pixabay.com/video/2024/12/11/246243_large.mp4 |
| `mountain-rain.mp4` | https://cdn.pixabay.com/video/2023/06/23/168447-839220680_small.mp4 |
| `rain-on-the-glass.mp4` | https://cdn.pixabay.com/video/2017/08/30/11722-231759069_large.mp4 |
| `reading-lamp-cat.mp4` | https://cdn.pixabay.com/video/2025/10/27/312345_large.mp4 |
| `retro-room-rain.mp4` | https://cdn.pixabay.com/video/2026/07/11/363351_large.mp4 |
| `rooftop-tram.mp4` | https://cdn.pixabay.com/video/2025/07/31/294606_large.mp4 |
| `snow-day-strings.mp4` | https://cdn.pixabay.com/video/2025/08/11/296693_large.mp4 |
| `snowfall-cafe.mp4` | https://cdn.pixabay.com/video/2024/11/23/242924_small.mp4 |
| `storm-watch.mp4` | https://cdn.pixabay.com/video/2025/02/13/257953_large.mp4 |
| `study-with-me.mp4` | https://cdn.pixabay.com/video/2025/04/13/271841_large.mp4 |
| `sunset-fence-cat.mp4` | https://cdn.pixabay.com/video/2025/04/07/270507_large.mp4 |
| `winter-cafe-lights.mp4` | https://cdn.pixabay.com/video/2024/11/26/243342_small.mp4 |
