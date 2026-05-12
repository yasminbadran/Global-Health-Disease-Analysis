# Global-Health-Disease-Analysis
A Python data analysis and visualization project that collects global disease and COVID-19 data from WHO API and Worldometer, cleans and processes the data using Pandas, and creates interactive visualizations including maps, heatmaps, 3D charts, and network graphs.

# Global Health Disease Analysis

## Overview
This project focuses on collecting, cleaning, analyzing, and visualizing global disease and COVID-19 data using Python.

The project combines data from multiple sources such as WHO API and Worldometer, then applies data preprocessing and visualization techniques to better understand disease distribution across countries.

## Features
- Collect disease indicators from WHO API
- Scrape COVID-19 data from Worldometer
- Clean and organize health datasets
- Convert country codes into full country names
- Export cleaned data into CSV and Excel files
- Visualize disease trends using charts and maps
- Create heatmaps, choropleth maps, bubble maps, and 3D visualizations
- Build a disease-country network graph using NetworkX
- Apply simple image processing using convolution filters

## Technologies Used
- Python
- Pandas
- Requests
- BeautifulSoup
- Selenium
- Plotly
- Matplotlib
- Seaborn
- NetworkX
- PyCountry

## Project Structure
```text
Global-Health-Disease-Analysis/
│
├── 202505432.ipynb
├── README.md
├── BIG_disease_data.csv
├── worldometer_covid_exact_table.csv
├── selenium_covid_data.csv
└── Full_Health_Descriptions.xlsx
