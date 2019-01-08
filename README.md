# (nb_)
This repository contains a collection of `jupyter notebooks` which focus on solving problems with `python` in the geospatial area of analytics. Key problems are detailed below;
- Geocoding
- Reverse Geocoding
- Spatial Joins
- Euclidean Distance

# Setup 
These mini projects rely on `python3`. To get started you will need the following libraries.
- `pandas`
- `gdal`
- `fiona`
- `shapely`
- `jupyter`
- `selenium`

note: `gdal` needs to be installed before 

** installation example: **
```sh
pip install gdal
```

# Instructions
After installing the relevant `python` modules you can open any of the following notebooks;
- `notebook_append_lga_codes_revised_with_apply.ipynb` - Attempts to append properly formatted Local Government Area (LGA) codes from the Australian Bureau of Statistics to messy free text Local Government Area names.
- `notebook_geocode.ipynb` - Uses a ghost browser (selenium) to access a geocoding service.
- `notebook_reverese_geocode.ipynb` - Uses a ghost browser (selenium) to access a reverse geocoding service.
- `notebook_spatial_joins_no_rtree.ipynb` - Utilises spatial joins to apply Local Government Area codes to longitude/latitude coordinates.
- `notebook_spatial_joins_rtree.ipynb` - Utilises spatial joins to apply Local Government Area codes to longitude/latitude coordinates. In addition to spatial join this notebook uses the rtree algorithm, which significantly improves processing time.
- `.ipynb`

# Contributors
- Daniel Corcoran

# Tests
- All notebooks have been tested and produce the outputs intended, granted inputs are correct, and modules are installed correctly.

# Sources
- [Australian Bureau of Statistics - Local Government Areas ASGS Ed 2018 Digital Boundaries in ESRI Shapefile Format](http://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/1270.0.55.003July%202018?OpenDocument)
- [Selenium Quick Start Guide](https://selenium-python.readthedocs.io/getting-started.html)
- [Web Driver Downloads for Selenium](https://github.com/mozilla/geckodriver/releases)
- [RTree Documentation](http://toblerity.org/rtree/)
