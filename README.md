# Hello World PWA

This repository contains a minimal Progressive Web App (PWA) that displays a simple "Hello, World!" message. It can be installed on mobile devices such as an iPhone.

## Prerequisites

- [Python 3](https://www.python.org/) **or** [Node.js](https://nodejs.org/)
- A modern browser with PWA support (Chrome, Edge, Safari on iOS 16+, etc.)

## Running Locally

1. Clone this repository and change into the project directory:

   ```bash
   git clone <repository-url>
   cd codex-playground
   ```

2. Start a static file server. Choose one of the following options:

   - **Python 3**

     ```bash
     python3 -m http.server 8080
     ```

   - **Node.js** (requires the `serve` package, install with `npm install -g serve`)

     ```bash
     npx serve -l 8080
     ```

   Leave the terminal running while you test the app. Press `Ctrl+C` to stop the server when you're done.

3. Open a browser and navigate to `http://localhost:8080/`. You should see "Hello, World!" on the page.

## Installing the PWA

1. **Desktop (Chrome/Edge)** – Look for the install icon in the address bar or open the browser menu and choose **Install**.
2. **iOS Safari** – Tap the **Share** button and select **Add to Home Screen**.
3. Launch the installed app from your home screen. It will open in a standalone window and work offline.

## Project Structure

The PWA consists of:

- `index.html` – registers the service worker.
- `manifest.json` – PWA manifest containing app metadata and icon.
- `service-worker.js` – simple cache-first service worker.
