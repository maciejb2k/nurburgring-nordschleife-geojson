# Nürburgring Nordschleife Touristenfahrten GeoJSON

A GeoJSON file tracing the Nürburgring Nordschleife circuit as driven during **Touristenfahrten** (not the GP circuit, not the full combined layout, just the tourist route).

## File

[`touristenfahrten.geojson`](touristenfahrten.geojson) - single `LineString` feature, ~3000 coordinate points.

## Usage

Load it into any tool that accepts GeoJSON:

- **[geojson.io/next](https://geojson.io/next)** - import and edit interactively in the browser

## Notes

- Coordinate system: WGS84 (EPSG:4326)
- Source: found a GPX file online, but the points had a noticeable offset from the actual road, so the track had to be manually realigned
- The GitHub map preview may look slightly off due to the satellite imagery offset used by GitHub's renderer. When loaded in geojson.io/next or a Leaflet map, the track aligns correctly with the road
