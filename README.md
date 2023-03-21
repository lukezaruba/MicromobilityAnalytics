# Micromobility Analytics in Minneapolis, MN with ArcGIS

Spatiotemporal analytics in the Esri ecosystem for analyzing scooter trip origins and destinations in Minneapolis, MN.

## Repo Structure
- [data/](data/)
  - [sources.md](data/sources.md)
  - [outputs/](data/outputs)
  - [raw/](data/raw)
    - [Minneapolis_Communities.shp](data/raw/Communities)
    - [PW_Street_Centerline.shp](data/raw/PW_Street_Centerline)
    - Motorized_Foot_Scooter_Trips_2021.csv
  - [docs/](docs/)
    - [TSC Charts/](docs/TSC%20Charts/)
    - [CommunityODMatrix.png](docs/CommunityODMatrix.png)
    - [DailyTripCount.png](docs/DailyTripCount.png)
    - [DayOfWeekTripCount.png](docs/DayOfWeekTripCount.png)
    - [HourOfDayTripCount.png](docs/HourOfDayTripCount.png)
- [notebooks/](notebooks/)
  - [1-etl.ipynb](notebooks/1-etl.ipynb)
  - [2-analysis.ipynb](notebooks/2-analysis.ipynb)
- [.gitignore](.gitignore)
- [README.md](README.md) (this file)

## Workflow
![Project Workflow](https://github.com/lukezaruba/MicromobilityForecasting/blob/main/docs/Micromobility%20Workflow.png?raw=true)
