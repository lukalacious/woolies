# Woolworths Urbanisation Proxy

Estimates how urban or rural a South African property is based on its proximity to Woolworths stores.

## Concept

Woolworths stores are concentrated in urban and affluent areas of South Africa. Distance to the nearest store serves as a proxy for urbanisation level, useful as a feature in property valuation models.

## Features

- **Geocoding** -- Converts addresses to coordinates via Nominatim (OpenStreetMap)
- **Proximity analysis** -- Geodesic distance to nearest Woolworths by store type (Full-line, Food, Convenience, Engen Foodstop)
- **Urbanisation scoring** -- 0-100 score based on distance and store density
- **Classification** -- Highly Urban / Urban / Suburban / Peri-urban / Rural
- **Interactive maps** -- Folium maps with colour-coded stores, proximity circles (5km/10km), and distance lines
- **Feature engineering** -- 12+ features for housing price modelling: distance by store type, store density at multiple radii, type diversity within 10km

## Coverage

30 Woolworths store locations across all 9 South African provinces.

## Tech Stack

Python, pandas, numpy, geopy, folium, beautifulsoup4, matplotlib, seaborn
