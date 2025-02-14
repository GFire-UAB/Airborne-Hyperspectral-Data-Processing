This code is © P. Sánchez and I. González, 2025, and it is made available under the GPL license enclosed with the software.
 
If you publish results using our algorithms, please acknowledge our work by citing the software directly as:
 
- Sánchez, P., González, I., Cortés, A., Carrillo, C., & Margalef, T. (2025). *Airborne Hyperspectral Data Processing* [Software]. Zenodo. [https://doi.org/10.5281/zenodo.14871861](https://doi.org/10.5281/zenodo.14871861)
 
This code was developed as part of the **SALUS (CPP2021-008762)** framework.

# Airborne-Hyperspectral-Data-Processing
This Jupyter notebook extracts wildfire perimeters from remote sensing data, computing BAI, NDVI, and NDWI from RGBN and LWIR images. Burned areas are detected using high-percentile hotspots in BAI and LWIR. Hotspots smaller than 1% of the largest are discarded. A concave hull then refines the final burned area.
