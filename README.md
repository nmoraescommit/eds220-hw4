# EDS 220 - Assignment 4, Task 2

## Purpose
The purpose of this project is to visualize the impact of wildfires and fire burn scars through false color imagery. The project, focuses on the Thomas Fire (2017) which burned in Ventura and Santa Barbara counties, and seeks to create a final output of a visualization of the Thomas Fire burn scars. Through data visualization and exploration, in this project, we can obtain a better understanding of the processes of true and false color imaging, xarray.DataSet exploration, and environmental geospatial modelling.

## Repository Setup
This repository contains two notebooks, `hwk2-task4-fire-perimeter-MORAES.ipynb` and `hwk4-task2-false-color-MORAES.ipynb`. The former cleans and creates a GeoJSON file indicating the Thomas Fire Perimeter and the latter creates a false colour map overlaying the perimeter on an image of Santa Barbara County. In the '.gitignore', is the data folder as well as .ipynb_checkpoints.

## Data Access
The data required for these notebooks are in the 'data' folder, in the '.gitignore' of this repository. In order to run the core, you must import the libraries, as implemented, as well as the coded filepaths.

The fire perimeter data was obtained from https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436.
The landsat data is from https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2 and was accessed through the server at `/courses/EDS220/data/hwk4_landsat_data landsat8-2018-01-26-sb-simplified.nc`. This data was pre-processed to remove data outside land and coarsen the spatial resolution.

## References and Acknowledgements
This repository contains materials for the fourth assignment for the course [EDS 220 - Working with Environmental Datasets](https://meds-eds-220.github.io/MEDS-eds-220-course/).

- Thomas Fire Perimeter: Publisher CAL FIRE. (2024, May 14). State of California - california fire perimeters (all). Catalog. https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436 
- Assignment Reference and Cleaned Landsat Data Access : Galaz-Garcia, C. (n.d.). Assignment 4. assignment4 – EDS 220 - Working with Environmental Datasets. https://meds-eds-220.github.io/MEDS-eds-220-course/assignments/assignment4.html 
- Landsat Data: Microsoft Planetary Computer. Planetary Computer. (n.d.). https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2
