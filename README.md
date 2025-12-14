# Geospatial Data Analysis & Visualization

## Overview
This project demonstrates exploratory geospatial data analysis using Python.  
The focus is on loading real-world geographic data, performing basic preprocessing, and creating clear, interactive visualizations to extract descriptive insights.

The project emphasizes **data understanding and visualization**, not prediction or modeling.

---

## Dataset
The dataset is sourced from the **USGS Earthquake Data Feed**, provided in CSV format.

- Contains global earthquake records
- Includes latitude, longitude, magnitude, depth, time, and location
- Publicly available and regularly updated

Data source is loaded directly via URL during execution.

---

## Tools & Libraries
- **Python**
- **pandas** – data loading and preprocessing
- **Plotly** – interactive geospatial and statistical visualizations
- **Jupyter Notebook** (Google Colab compatible)

---

## Data Preprocessing
The following preprocessing steps were applied:
- Removed rows with missing latitude or longitude values
- Filtered out very low-magnitude events to reduce noise
- Converted timestamp fields to datetime format
- Reset index after filtering

These steps ensure the dataset is suitable for geospatial and temporal analysis.

---

## Exploratory Analysis & Visualizations

### 1. Global Earthquake Distribution (Interactive Map)
An interactive map visualizes earthquake locations worldwide, with marker size and color representing magnitude.

**Insight:**  
Higher magnitude earthquakes are primarily observed along known tectonic plate boundaries.

---

### 2. Temporal Distribution of Earthquakes
A histogram shows how earthquake occurrences vary over time.

**Insight:**  
Earthquake occurrences show temporal variability, with certain periods having higher recorded activity.

---

### 3. Depth vs Magnitude Analysis
A scatter plot explores the relationship between earthquake depth and magnitude.

**Insight:**  
There is no clear linear relationship between earthquake depth and magnitude.

---

## Project Structure
