# ColonyCaller

Hands-free colony counting for CFU assays. Say the colony type; the page tallies it per plate.
Speech recognition runs on your own device (nothing is sent anywhere), so it works offline after the first load.

**Open it:** the GitHub Pages address for this repository (Settings → Pages).

**On a phone:** open the address in Safari (iPhone) or Chrome (Android), allow the microphone, then
Share → *Add to Home Screen* for a full-screen app icon.

## Files

| File | Purpose |
|---|---|
| `colonycaller.html` | The whole app (edit this to change defaults; see `DEFAULT_CATS` near the top of the script) |
| `index.html` | Redirects the site root to the app |
| `vosk.js` | On-device speech engine (vosk-browser, WebAssembly) |
| `model.tar.gz` | English speech model (`vosk-model-small-en-us-0.15`, repacked as tar.gz) |
| `manifest.webmanifest`, `icon.png` | Home-screen / app icon metadata |

Counts are stored in each browser. Download the CSVs to keep a permanent record.
