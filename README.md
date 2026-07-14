# DC Next Arrivals

A single-page, dot-matrix-style board showing the nearest WMATA Metrorail and Metrobus arrivals for your current location.

Uses the browser's geolocation to find the closest station/stop, then polls the WMATA API for live predictions, auto-refreshing every 30 seconds.

## Setup

This app requires a free API key from [developer.wmata.com](https://developer.wmata.com) (sign up → Products → Default Tier → subscribe). No backend or build step needed — the key is entered directly in the app on first load and stored only on your device.

## Usage

Just open `index.html` in a browser (or visit the deployed GitHub Pages site), allow location access, and paste in your WMATA API key when prompted.
