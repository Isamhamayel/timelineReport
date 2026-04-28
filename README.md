# Bazytrack Go Timeline Report

GitHub Pages version with the same report screen: device, from/to date, from/to time, timeline, table, map, geofence, Excel, PDF, and selected-row text.

## Host on GitHub Pages

1. Upload `index.html` to your GitHub repository root.
2. Go to **Settings > Pages**.
3. Choose **Deploy from branch**.
4. Choose branch `main` and folder `/root`.
5. Open the GitHub Pages link.

## Configuration

Inside `index.html`, edit this block if needed:

```js
const APP_CONFIG = {
  baseUrl: 'https://go.bazytrack.jo',
  token: ''
};
```

You can keep `token` empty and pass it from your existing system URL if that is how your current Apps Script page is opened.
