# HOMA Index Calculator PWA

A Progressive Web App for calculating HOMA (Homeostatic Model Assessment) index based on fasting glucose and insulin levels.

## Setup for GitHub Pages

1. Place your app icons in the `icons` directory:
   - `icon-192x192.png` (192x192 pixels)
   - `icon-512x512.png` (512x512 pixels)

2. Enable GitHub Pages in your repository settings:
   - Go to Settings > Pages
   - Select the branch you want to deploy (usually `main` or `master`)
   - Save the settings

3. Your PWA will be available at: `https://[your-username].github.io/homa/`

## Features

- Calculate HOMA index from glucose and insulin levels
- Works offline
- Installable on iOS and Android devices
- Visual indication when HOMA index exceeds 2.7

## Development

To test locally, you'll need to serve the files through a web server. You can use Python's built-in server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## PWA Installation

### On iOS:
1. Open Safari and navigate to the web app
2. Tap the Share button
3. Select "Add to Home Screen"
4. Give your app a name and tap "Add"

### On Android:
1. Open Chrome and navigate to the web app
2. Tap the menu button (three dots)
3. Select "Add to Home screen"
4. Follow the prompts to install
