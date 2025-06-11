# guia_geo

A collection of geospatial analysis notebooks showcasing data processing and visualization techniques.

## Installation

Create a Python environment with the required libraries. Python 3.9 or newer is recommended. Install dependencies with:

```bash
pip install geopandas folium pandas numpy matplotlib rasterio seaborn shapely tqdm
```

## Running the notebooks

Launch Jupyter and open any of the `.ipynb` files. The notebooks expect the data located in the `datasets/` directory relative to the repository root. Execute the cells in order to reproduce the examples.

## Datasets

Sample datasets used by the notebooks are stored in the `datasets/` folder. They include shapefiles, CSV tables and raster data. Typical dataset sizes range from a few megabytes up to about 65 MB each as shown by `du -sh datasets/*`.

```
18M    datasets/BR_UF_2023
6.9M   datasets/RJ_2023
5.4M   datasets/Sao_Paulo
19M    datasets/Singapore
88K    datasets/World_Temp_geotiff
5.4M   datasets/br_states.json
15M    datasets/solar_potential
65M    datasets/temp_sea_bottom
```

Use these files to run the notebooks locally.

