# Forest Fire Prediction in Algeria

This repository contains the Exploratory Data Analysis (EDA) and the implementation of machine learning algorithms applied to the Algerian forest fires dataset. The goal of this project is to predict future forest fires in Algeria by analyzing historical data and training machine learning models.

## About the Dataset

The dataset used in this project contains information about forest fires that occurred in two regions of Algeria: Bejaia and Sidi Bel-Abbes, from June to September 2012. The data includes the following features:

- **Date (DD/MM/YYYY)**: The day, month (June to September), and year (2012).
- **Weather Data Observations**:
  - **Temp**: Maximum temperature (in Celsius) at noon (22°C to 42°C).
  - **RH**: Relative Humidity in percentage (21% to 90%).
  - **Ws**: Wind Speed in km/h (6 km/h to 29 km/h).
  - **Rain**: Total rainfall during the day (in mm, ranging from 0 mm to 16.8 mm).
  
- **FWI Components** (From the Fire Weather Index system):
  - **FFMC**: Fine Fuel Moisture Code index (28.6 to 92.5).
  - **DMC**: Duff Moisture Code index (1.1 to 65.9).
  - **DC**: Drought Code index (7 to 220.4).
  - **ISI**: Initial Spread Index index (0 to 18.5).
  - **BUI**: Buildup Index index (1.1 to 68).
  - **FWI**: Fire Weather Index (0 to 31.1).

- **Classes**: Two classes indicating whether a fire occurred: 
  - **Fire** (1)
  - **No Fire** (0)

This dataset provides valuable insights into the patterns and causes of forest fires in Algeria and can be used to predict future occurrences of forest fires.

The dataset is taken from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/547/algerian+forest+fires+dataset).

## Exploratory Data Analysis (EDA)

In the EDA section, the dataset is analyzed and visualized to gain insights into the patterns and trends of forest fires in Algeria. Additionally, the data is pre-processed to prepare it for use in machine learning models.

