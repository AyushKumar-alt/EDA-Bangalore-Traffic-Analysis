# README: Bengaluru Traffic Analysis Project

## Project Title
**Exploratory Data Analysis on Bengaluru Traffic Dataset**

## Authors
- **Anusha** (2023UG000166)
- **Ahmed** (2023UG000114)
- **Ayush** (2023UG000116)

## Project Description
This project aims to analyze Bengaluru's traffic patterns to identify solutions for improving traffic control. The dataset provides insights into various traffic parameters such as traffic volume, average speed, congestion levels, travel time index, and environmental impact.

## Problem Statement
**Analyzing Bengaluru traffic patterns and identifying solutions for traffic control.**

## Goals
1. **Understanding Traffic Trends:** Identify how traffic volume and average speed vary across locations and seasons.
2. **Congestion Factor Analysis:** Examine the influence of weather, incidents, and road capacity utilization on congestion.
3. **Public Transportation Analysis:** Assess the role of public transport in reducing traffic congestion.
4. **Environmental Impact Assessment:** Study the correlation between environmental parameters and traffic patterns.
5. **Traffic Signal Compliance:** Explore its effect on average speed and congestion levels.

## Dataset Details
The dataset includes the following features:
- **Date**: Date when data was recorded.
- **Area Name**: Location within Bengaluru.
- **Road/Intersection Name**: Specific point where traffic data was recorded.
- **Traffic Volume**: Number of vehicles passing a given location.
- **Average Speed**: Mean speed of vehicles in the area.
- **Travel Time Index**: Ratio of travel time during peak vs free-flow conditions.
- **Congestion Level**: Degree of congestion in the area.
- **Road Capacity Utilization**: Percentage of the road's capacity in use.
- **Incident Reports**: Reported traffic incidents.
- **Environmental Impact**: Noise levels, emissions, and air quality indicators.
- **Public Transport Usage**: Number of people relying on public transportation.
- **Traffic Signal Compliance**: Percentage of vehicles following traffic signals.
- **Parking Usage**: Parking demand in specific areas.
- **Pedestrian and Cyclist Count**: Number of pedestrians and cyclists recorded.
- **Weather Conditions**: Recorded weather during data collection.
- **Roadwork and Construction Activity**: Indications of ongoing roadwork.

## Data Cleaning Process
- **Handling Missing Values:** Missing data was filled using:
  - Mean/Median for numerical values
  - Mode for categorical data
- **Normalization:** To account for varying ranges across columns
- **Unit Clarification:** Ensured consistent measurement units across features

## Key Insights and Solutions
- **High Traffic Volume Areas:** Koramangala reported the highest congestion with low average speed.
- **Incident-Prone Zones:** Areas like M.G. Road and Indiranagar showed increased incidents due to congestion.
- **Public Transport Impact:** Yeshwanthpur's high public transport usage contributed to reduced traffic volume.
- **Environmental Impact:** Uniform distribution of environmental concerns across weather conditions.

### Recommended Solutions
- **Traffic Signal Optimization**
- **Public Transport Enhancements**
- **Parking Management Strategies**
- **Cycling and Pedestrian Infrastructure Improvements**
- **Smart Traffic Management Systems**
- **Flexible Work Hours to Reduce Peak-Time Congestion**

## Technology Stack
- **Python** (Pandas, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Data Visualization Tools**

## Installation and Setup
1. Clone the repository:
```
git clone https://github.com/Anusha751/eda-bangalore-traffic-analysis.git
```
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Run the analysis:
```
python main.py
```

## Project Structure
```
├── data
│   └── bangalore_traffic_dataset.csv
├── notebooks
│   └── EDA_Bangalore_Traffic.ipynb
├── src
│   ├── data_cleaning.py
│   ├── data_analysis.py
│   └── visualization.py
├── README.md
├── requirements.txt
├── main.py
```

## Results
The project identifies key factors affecting Bengaluru's traffic congestion and provides actionable insights to improve traffic flow, reduce incidents, and enhance public transportation usage.

## Future Scope
- Implementing machine learning models for traffic prediction
- Developing a dashboard for real-time traffic monitoring

## Contributors
- **Anusha**  
- **Ahmed**  
- **Ayush**

## License
This project is licensed under the MIT License.

## GitHub URLs
- [Anusha's Repository](https://github.com/Anusha751/eda-bangalore-traffic-analysis)
- [Ayush's Repository](https://github.com/AyushKumar-alt/EDA-Bangalore-Traffic-Analysis)

---


