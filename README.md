# Chinook Weather

Calgary-tuned weather web app (installable on Android as an app).

- **Official:** Environment and Climate Change Canada city forecast, hourly forecast, warnings and current observations (api.weather.gc.ca)
- **Models:** Canada HRDPS 2.5 km, RDPS 10 km, GDPS, ECMWF IFS, ECMWF AIFS (AI), NOAA GFS/HRRR, DWD ICON, via Open-Meteo (CC BY 4.0)
- **Optional:** Google Weather API (add your own key in Settings; stored only on the device)
- **Radar:** ECCC GeoMet 1 km radar (snow/rain), last hour, animated

## Install on a Pixel
1. Open the site in Chrome on the phone.
2. Chrome menu (⋮) → **Add to home screen** → **Install**.
3. It opens full-screen from the home screen and app drawer like any other app.

## Files
- `index.html`: the whole app (HTML, CSS, JS)
- `manifest.webmanifest`, `icons/`: app name and icons
- `sw.js`: service worker so the app opens offline with the last saved forecast

No build step. Static hosting only (GitHub Pages, Netlify, any web server with HTTPS).
