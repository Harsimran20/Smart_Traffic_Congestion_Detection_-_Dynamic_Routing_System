# 🚦 Smart Traffic Congestion Detection & Travel Time Prediction 🛣️

This project leverages data science and machine learning to detect traffic congestion and predict travel times using geospatial, weather, and traffic data. It includes real-time visual mapping and predictive modeling to support urban traffic management and route optimization.

---

## 🧠 Key Features

- 🔍 **Congestion Classification**: Detect congested zones using `XGBoost` based on real-time traffic metrics.
- ⏱️ **Travel Time Prediction**: Estimate segment-level travel times using `GradientBoostingRegressor`.
- 🌍 **Interactive Mapping**: Generate color-coded traffic maps with tooltips for speed, volume, and travel time.
- 📊 **Feature Engineering**: Integrates time, weather, and volume for accurate predictions.
- 📂 **Data Preprocessing**: Standardized, timestamped dataset for model training and evaluation.

---

## 📁 Project Structure

📦 Traffic-Congestion-Detection

- ├── 📜 traffic_data_sample.csv # Source dataset
- ├── 📊 model_training.py # Training and evaluation scripts
- ├── 🌐 traffic_congestion_map.html # Output interactive map
- ├── 🧾 README.md # Project documentation

---

## 🔧 Technologies Used

- **Python 3.x**
- `pandas`, `numpy` for data handling
- `xgboost`, `sklearn` for ML models
- `folium`, `branca` for map visualization
- `matplotlib` (optional) for plotting trends

---

## 🗺️ Map Visualization

Traffic congestion levels are visually represented:

- 🟥 **Red**: Congested (speed < 10 km/h)
- 🟩 **Green**: Normal traffic

Tooltips provide:
- Current **speed**
- Estimated **travel time**
- Recorded **traffic volume**

View the map:

traffic_congestion_detailed_map.html

📌 Sample Use Cases
🚔 City Planning Departments: Optimize traffic light timing or reroute heavy traffic.

🚗 Navigation Apps: Integrate congestion scoring into route suggestion logic.

🏥 Emergency Services: Predict the fastest routes dynamically.

🌐 Smart City Platforms: Real-time mobility analytics dashboards.



