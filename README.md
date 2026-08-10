# Brigantine Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Brigantine municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01410600, Atlantic City Marina
- PETSS / NOAA station: 8534638
- NAVD88 thresholds: 3.31 ft minor, 4.31 ft moderate, 5.31 ft major
- MLLW thresholds: 5.7 ft minor, 6.7 ft moderate, 7.7 ft major
- MLLW = NAVD88 + 2.39 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Brigantine boundary at 9.3-foot adaptive resolution.
