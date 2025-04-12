# 🏋️‍♂️ Fitness Tracker – Data Analysis & Visualization

This project focuses on analyzing and visualizing personal health and fitness data by combining Exploratory Data Analysis (EDA), interactive visualizations with Plotly, and key insights into activity levels, sleep, heart rate, and more.

---

## 📂 Project Contents

- **Main notebook**: `FitnessTracker.ipynb`
- **Data source**: CSV file with daily fitness metrics
- **Language**: Python
- **Key libraries**: `pandas`, `plotly`, `statsmodels`, `numpy`

---

## 📊 Dataset – Data Dictionary

| Column | Description |
|--------|-------------|
| `date` | Date of entry |
| `steps` | Total daily step count |
| `weight` | Body weight in kilograms |
| `resting_heart_rate` | Resting heart rate (BPM) |
| `sleep_hours` | Total sleep duration (hours) |
| `active_minutes` | Total minutes of physical activity |
| `total_calories_burned` | Total daily energy expenditure |
| `fat_burn_minutes` | Time spent in fat burn heart rate zone |
| `cardio_minutes` | Time in cardio heart rate zone |
| `peak_minutes` | Time in peak heart rate zone |
| `workout_type` | Type of workout performed |
| `workout_duration` | Duration of workout session (minutes) |
| `workout_calories` | Calories burned during workout |
| `workout_avg_hr` | Average heart rate during workout |
| `workout_max_hr` | Maximum heart rate during workout |

---

## 🔍 Notebook Structure

1. **Exploratory Data Analysis (EDA)**  
   - Descriptive statistics  
   - Missing values check  
   - Data cleaning  

2. **Feature Engineering**  
   - New columns such as weekend detection, net calories, etc.

3. **Data Visualization**  
   - Step distribution histograms  
   - Scatter plots with linear regression  
   - Interactive charts using Plotly

4. **Insights & Observations**  
   - Relationship between steps and calories burned  
   - Impact of sleep and resting heart rate  
   - Comparison of workout types

---

## ▶️ How to Run the Project

1. Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows
