# NYC Motor Vehicle Collisions Analysis

## Overview

This project analyzes motor vehicle collision data in New York City, focusing on time, location, and human impact.   
The dataset is sourced from [NYC OpenData](https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes).  

## Key Steps

- **Data Import & Exploration**: Loaded and explored the raw dataset to identify missing values and relevant columns.
- **Data Cleaning**: Removed irrelevant columns, handled missing values, and standardized borough names.
- **Geospatial Analysis**: Used geocoding to map collisions by borough and visualize hotspots.
- **Temporal Analysis**: Analyzed collision trends by hour, day, month, and year.
- **Impact Analysis**: Evaluated injuries and fatalities by borough.

## Tools & Frameworks

- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Folium, Geopandas
- **Data Source**: NYC OpenData (Motor Vehicle Collisions)
- **Visualization**: Interactive maps and bar charts for spatial and temporal trends

## Results

- Identified peak collision hours and days.
- Mapped high-risk areas using Folium heatmaps.
- Quantified human toll (injuries/deaths) by borough.

## Files

- `Motor_Vehicle_Collisions.csv`: Raw dataset.
- `output.csv`: Cleaned dataset with boroughs filled.
- Jupyter Notebook: Full analysis workflow.

## How to Use

1. Clone the repository.
2. Install dependencies (`pandas`, `folium`, `geopandas`).
3. Run the notebook to reproduce analyses.
