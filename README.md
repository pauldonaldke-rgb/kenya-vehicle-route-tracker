# Kenya Vehicle Route Tracker

A standalone browser demo for planning a route within Kenya and previewing an animated vehicle marker. The marker is simulated; this app does not track a real vehicle.

## Run

Open `vehicle-route-tracker.html` directly in a modern browser. No installation, build, or server is required. An internet connection is needed for the map and route services.

## External services and resources

- **Leaflet 1.9.4** CSS and JavaScript are loaded from `unpkg.com`.
- **OpenStreetMap** map tiles are loaded from `tile.openstreetmap.org`; map data attribution is included in the map.
- **Nominatim** (`nominatim.openstreetmap.org`) searches place names and addresses.
- **OSRM demo routing service** (`router.project-osrm.org`) provides driving-route geometry.

These are third-party services, so their availability, usage policies, and rate limits apply. Location searches and route requests are sent to the respective providers. For live tracking, connect an authorized vehicle/device location feed and obtain the driver's knowledge and consent.
