# Global TB Visualization Dashboard

An interactive data visualization project focused on global Tuberculosis (TB) incidence data. It provides multiple charts and an integrated dashboard to explore hierarchical, geographical, and temporal trends in TB cases from 2000 to 2017.

## 📊 Visualizations Included
- **Force-Directed Graph:** Shows country-region relationships with case-weighted edges.
- **Map Chart:** Displays geographic distribution and intensity of TB cases.
- **Timeline Line Chart:** Tracks TB case evolution by continent over time.
- **Treemap:** Hierarchical view of continents → regions → countries.
- **Sunburst Chart:** Circular hierarchical breakdown of global TB data.

## 🧹 Data Preprocessing
- Cleaned unnecessary columns.
- Imputed missing values using mean/mode strategies.
- Handled row-level missing data (years 2000–2017) using row-wise mean.

## 🖥️ Dashboard Features
- Embedded iframe visualizations with toggle buttons.
- Filters by year, region, or continent depending on the chart.
- Fully interactive: zoom, pan, hover, and drill-down capabilities.

## 📁 Dataset
Data Source:  
[Tuberculosis Incidence Dataset](https://data.amerigeoss.org/dataset/indicator-3-3-2-tuberculosis-incidence-per-100000-population/resource/c846bcb2-20a8-49d3-955a-046b52344c88)

## 🚀 Technologies Used
- HTML / CSS / JavaScript
- D3.js for charts
- Pandas for data cleaning
- Responsive iframe-based layout
