# Micromobility Analytics in Minneapolis, MN with ArcGIS

Spatial data science & spatiotemporal analytics in the Esri ecosystem for analyzing scooter trip origins and destinations in Minneapolis, MN.

## Repo Structure
- [data/](data/)
  - [sources.md](data/sources.md)
  - [outputs/](data/outputs)
  - [raw/](data/raw)
    - [Minneapolis_Communities.shp](data/raw/Communities)
    - [PW_Street_Centerline.shp](data/raw/PW_Street_Centerline)
    - Motorized_Foot_Scooter_Trips_2021.csv
  - [docs/](docs/)
    - [CommunityODMatrix.png](docs/CommunityODMatrix.png)
    - [DailyTripCount.png](docs/DailyTripCount.png)
    - [DayOfWeekTripCount.png](docs/DayOfWeekTripCount.png)
    - [HourOfDayTripCount.png](docs/HourOfDayTripCount.png)
- [notebooks/](notebooks/)
  - [analysis.ipynb](notebooks/analysis.ipynb)
  - [etl.ipynb](notebooks/etl.ipynb)
- [.gitignore](.gitignore)
- [README.md](README.md) (this file)

## Workflow
![Project Workflow](https://github.com/lukezaruba/MicromobilityForecasting/blob/main/docs/Micromobility%20Workflow.png?raw=true)

### Data
- 32 weeks in 2021 with data

### Methodology

- Time Series Clustering
  - Value
  - Profile (Correlation)
  - Profile (Fourier)
- Local Outlier Analysis
- Emerging Hot Spot Analysis

### Visualization
- Origins Heat Map & Tessellation
- Destinations Heat Map & Tessellation
- OD Tessellation Dot Density & OD Tessellation Bivariate
- OD Tessellation Centroid (Points)
- Time Series Clusters (2D)
- Local Outliers (2D)
- Emerging Hot Spot (3D)
