# Micromobility Forecasting in Minneapolis, MN with ArcGIS

A comparison of spatiotemporal prediction methods in the ArcGIS ecosystem for forecasting scooter trip origins and destinations in Minneapolis, MN.

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
  - [deeplearning.ipynb](notebooks/deeplearning.ipynb)
  - [etl.ipynb](notebooks/etl.ipynb)
  - [randomforest.ipynb](notebooks/randomforest.ipynb)
- [.gitignore](.gitignore)
- [README.md](README.md) (this file)

## Workflow
![Project Workflow](https://github.com/lukezaruba/MicromobilityForecasting/blob/main/docs/Micromobility%20Workflow.png?raw=true)

### Data
- 32 weeks in 2021 with data
- April through August will be used as training data
- September and October will be used as test data

### Methodology
- Forest-Based Forecast
  - Model Scale
    - Individual Location
    - Entire Cube
    - Time Series Cluster
- Deep Learning Forecast
  - Residual Neural Network (ResNet)
  - Fully Convolutional Network (FCN)
  - Long Short-Term Memory (LSTM)
