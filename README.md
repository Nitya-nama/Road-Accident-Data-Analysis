# Road-Accident-Data-Analysis
# 🚗 Road Accident Data Analysis

## 📌 Overview
This project analyzes road accident trends in India using Python and data science techniques. It explores accident patterns, hotspots, and influencing factors such as weather, time, and vehicle type.

## 📂 Files Included
- `India_Road_Accidents.csv` → Sample dataset of road accidents in India.
- `Road_Accident_Analysis.ipynb` → Jupyter Notebook for data cleaning, EDA, and visualization.
- `accident_heatmap.html` → Interactive heatmap showing accident-prone locations.
- `README.md` → Project documentation.

## 📊 Dataset Description
The dataset contains the following columns:

| Column Name          | Description |
|----------------------|-------------|
| `Accident_ID`       | Unique accident identifier |
| `Accident_Date`     | Date of the accident |
| `Time`             | Time of accident |
| `City`             | City where accident occurred |
| `State`            | State where accident occurred |
| `Latitude`         | Latitude of accident location |
| `Longitude`        | Longitude of accident location |
| `Weather_Condition` | Weather at the time of accident |
| `Vehicle_Type`     | Type of vehicle involved (Car, Bike, Truck, etc.) |
| `Severity`         | Severity level (Minor, Moderate, Severe, Fatal) |

## 🛠 Setup & Requirements
### 1️⃣ Install Required Libraries
Run the following command to install dependencies:
```bash
pip install pandas numpy matplotlib seaborn folium
2️⃣ Run the Jupyter Notebook
Launch Jupyter Notebook and open Road_Accident_Analysis.ipynb to execute the analysis.

📌 Key Insights & Visualizations
✔ Accident trends by year, month, time of day
✔ Accident hotspots using geospatial heatmaps
✔ Impact of weather conditions on accident severity
✔ Vehicle-type distribution in accidents

📍 Heatmap Visualization
After running the notebook, an interactive heatmap will be saved as accident_heatmap.html. Open it in a browser to view accident-prone areas.

🤝 Contributing
Feel free to improve the dataset, add new visualizations, or suggest optimizations! 🚀
