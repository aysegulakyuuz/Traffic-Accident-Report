# UK Traffic Accident Analysis (2005–2014)

## 📌 Project Overview

This project analyzes road traffic accidents in the United Kingdom using official datasets from 2005 to 2014. The data covers over 1.6 million records, including location coordinates, accident severity, number of casualties, and road types.

## 🎯 Objectives

- How does traffic volume affect accident frequency?
- What factors increase the likelihood of accidents?
- Can we forecast accident rates over time?
- How do urban and rural areas differ in accident patterns?

## 📁 Dataset

https://www.kaggle.com/datasets/daveianhickey/2000-16-traffic-flow-england-scotland-wales

## 🧪 Key Features

- `Date`, `Year`, `Month`
- `Accident_Severity` (Fatal / Serious / Slight)
- `Number_of_Vehicles`, `Number_of_Casualties`
- `Urban_or_Rural_Area`
- `Latitude`, `Longitude`

## 🛠️ Technologies Used

- **Python (Pandas, NumPy)** – Data processing  
- **Matplotlib / Seaborn** – Visualizations  
- **Plotly** – Interactive maps  
- **Prophet** – Time series forecasting  

## 📊 Analysis & Outputs

- Bar chart: Yearly accident counts
- Countplot: Urban vs Rural accidents
- Countplot: Severity levels
- Heatmap: Correlation between numeric features
- Mapbox scatter plot: Geographical accident clusters
- Forecast: Annual accident predictions using Prophet (2015–2019)

## 🧠 Forecasting (Prophet)

A time-series model was trained on yearly aggregated accident data (2005–2014) to predict future accident rates for 2015–2019 using Prophet.


## 👩‍💻 Author

**Ayşegül Akyüz**  



