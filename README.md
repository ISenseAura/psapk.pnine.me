# psapk.pnine.me

Landing page for **PS-X** (PS Experience) — unofficial Pokémon Showdown for Android.

Site source lives here; deploy to the server path referenced in `nginx/psapk.pnine.me.conf`.

## Publishing a new APK

1. Build in `ps-mobile`: `npm run build:apk`
2. Copy the release APK here:
   ```bash
   cp ../pokemon-showdown-client/ps-mobile/website/downloads/ps-x-1.2.0.apk downloads/ps-x-1.2.0.apk
   cp downloads/ps-x-1.2.0.apk downloads/ps-x.apk
   ```
3. Update `index.html` (hero version, What's new) and `about.html` if needed.
4. Patch notes: `ps-mobile/docs/patch-notes.md`
5. Deploy / push to the server.
