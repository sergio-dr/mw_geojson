# Milky Way GeoJSON
These files contain geometries outlining the Milky Way isophotes at five levels of surface brightness.

The files are based on the 
[one provided on the d3-celestial plugin by Olaf Frohn](https://github.com/ofrohn/d3-celestial/blob/master/data/mw.json) with [cleanup by Diego Hernangómez](https://github.com/dieghernan/celestial_data/blob/main/data/mw.geojson). 

For **`mw.json`**, using [geojson.io](https://geojson.io) I reworked manually the polygons at the -180º=180º RA boundary to avoid large gaps.

For **`mw_simplified.json`** I also used [mapshaper.org](https://mapshaper.org) '`simplify`' command (with `percentage=43%`). This allowed for a >50% reduction in file size with very little degradation of the polygons. 

Both files were exported with [mapshaper.org](https://mapshaper.org) back to GeoJSON using the parameter `precision=0.001` as the original. 


## Data Structure
**id**: Milky Way outlines in 5 brightness steps (ol1-ol5).


## References
Frohn O, Hernangómez D (2023). “Celestial Data.”
<doi:10.5281/zenodo.7561601> <https://doi.org/10.5281/zenodo.7561601>,
<https://dieghernan.github.io/celestial_data/>.
