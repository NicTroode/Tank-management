# Tank Log

A phone app for logging aquarium water tests. It tracks each test against healthy ranges for the tank's profile, charts trends, gives recommendations, and checks which species can live together.

It runs entirely in the browser. Tests are saved on the phone itself, so nothing is sent anywhere. Use **Backup** in the top corner to save a copy of your data now and then.

## Install on your phone

1. In this repository, open **Settings → Pages**. Under *Build and deployment*, set **Source** to *Deploy from a branch*, choose **main** and **/ (root)**, then **Save**.
2. After a minute, the app is live at `https://nictroode.github.io/Tank-management/`.
3. **iPhone:** open that link in Safari, tap **Share → Add to Home Screen**.
   **Android:** open it in Chrome, tap the **⋮** menu → **Install app**.

## Bring across history from the Claude version

1. In Tank Log inside Claude, tap **Export** and save the file.
2. In the phone app, tap **Backup → Restore from file** and choose that file.

## Files

| File | What it does |
| --- | --- |
| `index.html` | The whole app |
| `manifest.webmanifest` | Name, icon and colours for installing to the home screen |
| `sw.js` | Lets the app open offline. Change `CACHE` when updating so phones get the new version |
| `icon*.png`, `icon.svg` | App icons |
