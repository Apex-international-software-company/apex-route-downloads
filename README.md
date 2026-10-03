# apex-route-downloads
APEX Route phone install files (public, free to download, no account needed).

- **App APKs:** see Releases (`v1.0.0-rc*`). Each installs over the previous one.
- **Offline state maps:** release `maps-2026-10-02` holds per-state files
  (`<STATE>_map.pmtiles`, `<STATE>_routing.tar.gz`, `<STATE>_search.db.gz`). The app downloads them
  from **Settings → Offline Maps**. You don't need to download them by hand.
- **Catalog the app reads:** [`catalog/us-states.json`](catalog/us-states.json) (fallback copy on the `maps-catalog` release).

States in the current catalog: AL, AR, AZ, CO, GA, KS, KY, MO, MS, NC, NM, OK, SC, TN, TX, UT.

Map data © OpenStreetMap contributors (ODbL), © OpenMapTiles. Routing tiles built with Valhalla 3.6.3.
