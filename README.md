# Airborne-Hyperspectral-Data-Processing
This Jupyter notebook extracts wildfire perimeters from remote sensing data, computing BAI, NDVI, and NDWI from RGBN and LWIR images. Burned areas are detected using high-percentile hotspots in BAI and LWIR. Hotspots smaller than 1% of the largest are discarded. A concave hull then refines the final burned area.
