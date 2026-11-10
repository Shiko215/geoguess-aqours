# GeoGuessAqours

**Aurora Studio Presents** — Love Live! Sunshine!! anime location challenge.

A static HTML5 game featuring 159 Numazu / Uchiura scenes from seasons 1 and 2, an interactive map, five-round scoring, 30/60/120-second timers, and downloadable 1080 × 1350 PNG scorecards.

## Run locally

```sh
python -m http.server 8080
```

Open http://localhost:8080. Serve over HTTP rather than opening index.html directly, because the game loads questions.json with fetch.

## GitHub Pages

In the repository settings, open **Pages**, choose **Deploy from a branch**, then select **main** and **/ (root)**. No build step, API key, or backend is required. All asset paths are relative and support repository subpaths.

## Credits

Unofficial fan project; not affiliated with the Love Live! rights holders. Anime images belong to their respective rights holders and are not covered by a software license. Location records and reference images come from Anitabi and its contributors:

- Season 1: https://www.anitabi.cn/map?bangumiId=165553
- Season 2: https://www.anitabi.cn/map?bangumiId=210272
- Map data: © OpenStreetMap contributors
- Map UI: Leaflet 1.9.4 (BSD-2-Clause)

Maps require an internet connection. The PNG share card is created locally in the browser. Personal best is stored in localStorage. No analytics or backend are included.
