# aiometadata-nuvio-assets

A collection of pure-vector SVG icons, cover tiles (`wide`, `square`, `poster` — static & hover-animated), and animated SVG intros built for **AIOMetadata** and **Nuvio**.

Started as a way to give the community crisp, lightweight, high-quality hover covers and platform intros without heavy video files or blurry raster images.

## What's Inside

### `icons/dark/` & `icons/light/` (10 icons × 2 themes)
Transparent-background vector logos for dark and light UIs:
`imdb`, `letterboxd`, `lumieredb`, `mdblist`, `metacritic`, `rotten-tomatoes`, `simkl`, `thetvdb`, `tmdb`, `trakt`

### `covers/static/` & `covers/animated/` (`wide/`, `square/`, `poster/`)
Full-bleed SVG cover tiles in all 3 Nuvio shapes (28 platforms, plus `_2` alternates):
- `wide/` (`1280×720`)
- `square/` (`720×720`)
- `poster/` (`600×900`)

`covers/static/` has clean static tiles. `covers/animated/` adds CSS hover-looping glow, sheen, and motion effects (with `prefers-reduced-motion` support).

### `covers/intros/` (35 SVGs)
Full-screen (`1280×720`) pure-SVG animated platform intros using the same slugs as the covers (with `_2` / `_3` suffixes for alternate versions).

### Supported Platforms
`amc-plus`, `apple-tv`, `canal-plus`, `crave`, `criterion-channel`, `crunchyroll`, `curiosity-stream`, `discovery-plus`, `disney-plus`, `hbo`, `hbo-max`, `hulu`, `max`, `mgm-plus`, `mubi`, `netflix`, `paramount-plus`, `peacock`, `plex`, `pluto-tv`, `prime-video`, `roku`, `showtime`, `shudder`, `skyshowtime`, `starz`, `tubi`, `youtube-originals`

## Direct CDN URLs (jsDelivr)

Once pushed to `main`, you can link directly to any asset:

```text
https://cdn.jsdelivr.net/gh/aBrihoum/aiometadata-nuvio-assets@main/icons/dark/trakt.svg
https://cdn.jsdelivr.net/gh/aBrihoum/aiometadata-nuvio-assets@main/covers/static/wide/peacock.svg
https://cdn.jsdelivr.net/gh/aBrihoum/aiometadata-nuvio-assets@main/covers/animated/poster/mubi.svg
https://cdn.jsdelivr.net/gh/aBrihoum/aiometadata-nuvio-assets@main/covers/intros/netflix.svg
```
