# Thomas Fire Impacts on Santa Barbara

## Purpose
The purpose of this project is to visualize the impact of wildfires and fire burn scars through false color imagery. There will also be preliminary investigation into the impacts on the air quality index in Santa Barbara, casued by the fire. The project, focuses on the Thomas Fire (2017) which burned in Ventura and Santa Barbara counties, and seeks to create a final output of a visualization of the Thomas Fire burn scars as well as a plot of the AQI index. Through data visualization and exploration, in this project, we can obtain a better understanding of the processes of true and false color imaging, xarray.DataSet exploration, and environmental geospatial modelling.

## Repository Setup
This repository contains three notebooks, `hwk2-task3-aqi.ipynb`, `hwk2-task4-fire-perimeter-MORAES.ipynb`, and `hwk4-task2-false-color-MORAES.ipynb`. The first provides a plot of the AQI index in Santa Barbara. Finally, the middle cleans and creates a GeoJSON file indicating the Thomas Fire Perimeter and the latter creates a false colour map overlaying the perimeter on an image of Santa Barbara County. In the '.gitignore', is the data folder as well as .ipynb_checkpoints.

## Data Access
The data required for these notebooks are in the 'data' folder, in the '.gitignore' of this repository. In order to run the code, you must import the libraries and filepaths, as coded.

The fire perimeter data was obtained from https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436.
The landsat data is from https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2 and was accessed through the server at `/courses/EDS220/data/hwk4_landsat_data landsat8-2018-01-26-sb-simplified.nc`. This data was pre-processed to remove data outside land and coarsen the spatial resolution.
The AQI data was gleaned from https://aqs.epa.gov/aqsweb/airdata/download_files.html#AQI.

## References and Acknowledgements
This repository contains materials for the second and fourth assignment for the course [EDS 220 - Working with Environmental Datasets](https://meds-eds-220.github.io/MEDS-eds-220-course/).

- Thomas Fire Perimeter: Publisher CAL FIRE. (2024, May 14). State of California - california fire perimeters (all). Catalog. https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436 
- Assignment Reference and Cleaned Landsat Data Access : Galaz-Garcia, C. (n.d.). Assignment 4. assignment4 – EDS 220 - Working with Environmental Datasets. https://meds-eds-220.github.io/MEDS-eds-220-course/assignments/assignment4.html 
- Landsat Data: Microsoft Planetary Computer. Planetary Computer. (n.d.). https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2
- Air Quality Index Data: Environmental Protection Agency. (n.d.). AirData website file download page. EPA. https://aqs.epa.gov/aqsweb/airdata/download_files.html#AQI 
