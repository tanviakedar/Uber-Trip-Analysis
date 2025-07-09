# Uber-Trip-Analysis
Exploratory data analysis of Uber trip data (Jan–Feb 2015) in NYC, focusing on dispatch base performance, trip volume trends, and vehicle efficiency using Python and pandas.

## 📁 Dataset Overview

- **File Used**: `Uber-Jan-Feb-FOIL.csv`
- **Source**: NYC TLC FOIL Data
- **Columns**:
  - `dispatching_base_number`: Uber base ID (e.g., B02512)
  - `date`: Activity date
  - `active_vehicles`: Number of active vehicles that day
  - `trips`: Number of Uber trips completed

## 🎯 Project Objectives

- Analyze total and daily trip trends
- Identify the most active dispatching bases
- Evaluate trip efficiency (trips per vehicle)
- Understand weekday and weekly patterns
- Visualize relationships using charts and plots

## 🧰 Tools & Technologies

- **Language**: Python
- **Libraries**: 
  - `pandas` – data manipulation
  - `matplotlib`, `seaborn` – data visualization
- *(Optional extensions)*: `plotly`, `folium`, `Power BI`

## 📊 Key Visualizations

- Daily and weekly trip line plots
- Base-wise total trips (bar chart)
- Trips vs Active Vehicles (scatter plot)
- Efficiency comparison (bar chart)
- Weekday heatmap of average trips
- Boxplots to show distribution per base


## 📈 Insights Summary

- **B02512** dispatched the most trips during the period.
- **Fridays and Thursdays** had the highest average demand.
- Efficiency (trips/vehicle) varied widely between bases.
- Clear weekly seasonality was observed in user demand.


## 🚀 How to Use

1. Clone the repository
2. Open `Uber_Trip_Analysis.ipynb` (or `Uber_Trip_Analysis.py`)
3. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
