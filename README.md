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
