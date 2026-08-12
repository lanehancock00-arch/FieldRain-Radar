[README.md](https://github.com/user-attachments/files/30997601/README.md)
# FieldRain Radar — MVP v2

This version adds:
- Street / satellite basemap toggle
- Esri World Imagery satellite layer
- Persistent multi-pin library
- Open, rename, and delete saved pins
- Multiple saved pins visible on the map at the same time
- Click any saved pin to load precipitation data
- GPS location
- Radar overlay
- Current precipitation estimate
- Past 24-hour precipitation
- Next 24-hour forecast precipitation

## Run locally

From this folder:

    python -m http.server 8000

Then open:

    http://localhost:8000

## Data sources
- OpenStreetMap: street basemap
- Esri World Imagery: satellite imagery
- RainViewer: radar overlay
- Open-Meteo: current/past/forecast point precipitation

## Recommended next version
- Draw actual field boundaries/polygons
- Calculate acreage
- Average radar-derived rainfall across each whole field
- FieldRain Radar live site
- Store 1h, 3h, 6h, 12h, 24h, 48h, and 72h rainfall totals
- Color-code pins/fields based on recent rainfall
- Add rainfall alerts
- Add cloud accounts so the library syncs between phone and desktop
