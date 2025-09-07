# Hello World PWA

This repository contains a minimal Progressive Web App (PWA) that displays a simple "Hello, World!" message. It can be installed on mobile devices such as an iPhone.

## Running Locally

1. Make sure you have a static file server installed. If you have Python, you can run:

   ```bash
   python3 -m http.server 8080
   ```

2. Open `http://localhost:8080` in your browser. On supported mobile browsers you should be prompted to install the app.

The PWA consists of:

- `index.html` – main page registering the service worker.
- `manifest.json` – PWA manifest with inline SVG icon and display settings.
- `service-worker.js` – simple cache-first service worker.
