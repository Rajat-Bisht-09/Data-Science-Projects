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

## PM10 Air Quality Estimation Project

This project focuses on predicting PM10 air quality levels using a machine learning approach. It involves several steps, from data preprocessing to model evaluation, with the goal of building a reliable predictive model. Below is an overview of the key stages of the project:

` Dependent Variable : PM10 `

### 1. Data Preprocessing
The dataset contains several environmental and pollutant-related features such as PM2.5, SO2, NO2, and meteorological variables. To prepare the data for modeling, the following steps were taken:
- **Handling Missing Values:** Missing data points were imputed using suitable strategies based on the type of data (e.g., mean imputation for continuous variables).
- **Handling Categorical Variables:** Categorical features such as wind direction (wd) were converted into numerical values using encoding techniques (e.g., one-hot encoding), ensuring they are suitable for input into machine learning algorithms.

### 2. Data Visualization
Exploratory data analysis (EDA) was conducted to understand the underlying trends and relationships in the dataset. Visualizations such as scatter plots, histograms, and correlation heatmaps were used to:
- Identify correlations between PM10 levels and other variables (e.g., temperature, wind speed, and other pollutants).
- Spot any potential outliers or anomalies in the data.

### 3. Model Building
Several machine learning models were built and trained to estimate PM10 levels. These models include:
- **Linear Regression**
- **Random Forest Regressor**
- **Decision Tree Regressor**
- **Gradient Boosting Regressor**
- **XGBoost**

Each model was trained on the preprocessed data, and hyperparameters were tuned to improve performance. The models were then evaluated based on their ability to accurately predict PM10 levels.

### 4. Evaluation and Comparison
The models were evaluated using **Root Mean Squared Error (RMSE)**, which provides insight into the average error of predictions. A comparison of the models was conducted to identify which algorithm performs best in terms of both accuracy and generalization.

### 5. Result Interpretation
The final model's predictions were interpreted by comparing the predicted PM10 levels with the actual values in the test dataset. Through this comparison, we assessed the model's reliability in estimating air quality, identifying areas where predictions could be improved or where more data might be needed.

## Appendix

For further information and detailed code implementation, please refer to the project notebook file included in this repository.
