# Barometric Pressure Visualizer

A client-side web app that displays 14 days of barometric pressure data (7 days past + 7 days forecast) for any location worldwide.

**Live app: https://dwhuang.github.io/barometry/**

## Features

- Sea-level pressure chart with observed (solid) and forecast (dashed) lines
- Rate-of-change chart showing rising (red) and falling (blue) pressure trends
- High/Low pressure reference bands (1030 / 1000 hPa)
- Auto-detect location via browser geolocation
- City search with typeahead dropdown
- Synchronized hover crosshair across both charts
- hPa / inHg unit toggle
- Shareable URLs with location encoded in the hash
- Fully client-side — no server required

## Data Sources

- **Weather data:** [Open-Meteo](https://open-meteo.com/) (free, no API key)
- **City search:** [Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api)
- **Reverse geocoding:** [Nominatim / OpenStreetMap](https://nominatim.openstreetmap.org/)

## Dependencies

- [Chart.js](https://www.chartjs.org/) (vendored, MIT license)
- [chartjs-adapter-date-fns](https://github.com/chartjs/chartjs-adapter-date-fns) (vendored, MIT license)
