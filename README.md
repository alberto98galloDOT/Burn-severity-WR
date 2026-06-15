# Southern Western Downs — Post-Fire Burn Severity Assessment

Interactive web map published via GitHub Pages.

**Live map:** https://alberto98gallodot.github.io/Burn-Scar--South-western-reg/

## Overview
Post-fire burn severity assessment for Southern Western Downs (Queensland) using the Differenced Normalised Burn Ratio (dNBR) derived from Landsat 9 OLI-2 Collection 2 Level-2 imagery. Pre-fire scene: September 2023 — Post-fire scene: December 2023.

## Layers
- **Burn Scar (dNBR)** — five burn severity classes calibrated against USGS/FIREMON thresholds (Key & Benson, 2006)
- **Severity × Land Use** — intersection of dNBR classes with QLUMP 2019 land use, aggregated into five macro-categories

## Burn Severity Classes
- High Severity
- Moderate-High Severity
- Moderate-Low Severity
- Low Severity
- No Change / Unburned

## Land Use Macro-Categories
- Grazing (modified pastures, native vegetation, intensive animal production)
- Cropping (dryland, irrigated, horticulture)
- Nature Conservation (nature conservation, managed resource protection, wetland, river)
- Infrastructure (residential, transport, manufacturing, mining, utilities)
- Other (minimal use, land in transition, waste treatment)

## Methodology
dNBR = NBR pre-fire − NBR post-fire. Landsat 9 OLI-2 Collection 2 Level-2 surface reflectance imagery downloaded from USGS Earth Explorer. Enhanced Regrowth class merged with Unburned to reduce seasonal agricultural noise. Intersected with QLUMP 2019 land use (ALUM Classification v8) to assess burn impact by land use type.

## Data Sources
- Landsat 9 OLI-2 Collection 2 Level-2: USGS Earth Explorer
- Land Use: QLUMP 2019 — Queensland Land Use Mapping Program (Queensland Spatial)
- Burn severity thresholds: Key, C.H. & Benson, N.C. (2006). USDA Forest Service RMRS-GTR-164

## Tools
QGIS 3.44 · QGIS2Web (Leaflet) · GitHub Pages

## Author
Alberto Gallo — GIS Analyst & Urban Planner
Graduate Member, Planning Institute of Australia (PIA)
