# Traffic Prediction Dataset

## Introduction

Traffic congestion and related problems are common concerns in urban areas. Understanding traffic patterns and analyzing data can provide valuable insights for transportation planning, infrastructure development, and congestion management.

## Dataset Overview

The **Traffic Prediction Dataset** contains information collected by a computer vision model. The model detects four classes of vehicles: cars, bikes, buses, and trucks. The dataset is stored in a CSV file and includes the following columns:

1. **Time in Hours**: The timestamp of the observation.
2. **Date**: The date of the observation.
3. **Day of the Week**: Indicates the day of the week (e.g., Monday, Tuesday).
4. **CarCount**: Number of detected cars.
5. **BikeCount**: Number of detected bikes.
6. **BusCount**: Number of detected buses.
7. **TruckCount**: Number of detected trucks.
8. **Total**: Total count of all vehicle types detected within a 15-minute duration.
9. **Traffic Situation**: Categorized into four classes: 1-Heavy, 2-High, 3-Normal, and 4-Low.

The dataset is updated every 15 minutes, providing a comprehensive view of traffic patterns over one month.

## Use Cases

The dataset is useful for:

- **Transportation Planning**: Understanding vehicle demand and identifying congested areas.
- **Congestion Management**: Targeted interventions like signal optimizations and lane adjustments.
- **Traffic Flow Analysis**: Studying patterns by hour, day, or specific dates.
- **Urban Planning**: Assessing traffic impact for zoning and infrastructure decisions.

## Repository Contents

- `Traffic Prediction.ipynb`: Jupyter notebook with data exploration and insights.
- `README.md`: Overview of the project (you're reading it now!).

Feel free to explore and contribute to this project! 🚗🌆

