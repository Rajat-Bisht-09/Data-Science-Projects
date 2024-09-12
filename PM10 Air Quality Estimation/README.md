## PM10 Air Quality Estimation 
Air quality is a critical factor in determining public health, with PM10 (particulate matter with a diameter of 10 microns or less) being one of the most harmful pollutants. Exposure to high levels of PM10 can lead to respiratory and cardiovascular issues. The challenge is that monitoring stations often provide limited coverage, making it difficult to accurately predict air quality across a large region.

### Data Description
| Column             | Description                                                       |
| -----------------  | ----------------------------------------------------------------- |
| No  | Unique identifier for each record |
| year| The year of the recorded data |
| month| The month of the recorded data |
| day | The day of the recorded data |
| hour  | The hour of the recorded data |
| PM2.5 | Concentration of fine particulate matter (≤ 2.5 microns) |
| PM10| Concentration of particulate matter (≤ 10 microns) |
| SO2 | Concentration of sulfur dioxide (SO₂) in the air |
| NO2  | Concentration of nitrogen dioxide (NO₂) in the air |
| CO | Concentration of carbon monoxide (CO) in the air |
| O3 | Concentration of ozone (O₃) in the air |
| TEMP | Ambient temperature in degrees Celsius |
| PRES  | Atmospheric pressure in hPa (hectopascals) |
| DEWP | Dew point temperature in degrees Celsius |
| RAIN| Amount of rainfall in millimeters |
| wd | Wind direction |
| WSPM | Wind speed in meters per second (m/s) |
| DateTime| Combined date and time of the record |
| Date | The date of the recorded data |

This project aims to address this gap by building a machine learning model that can estimate PM10 levels based on available environmental data. By leveraging features such as weather conditions, traffic data, and geographical information, the model provides an efficient way to predict PM10 levels in areas without direct monitoring, ultimately helping to inform public health decisions and reduce exposure to harmful pollutants.

## Evaluation Metric
The model performance is evaluated using Root Mean Squared Error (RMSE), which measures the average magnitude of the error between predicted and actual PM10 levels. RMSE is used to quantify how well the model's predictions align with the true values, with lower values indicating better accuracy and model performance.
