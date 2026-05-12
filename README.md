# Global Health Disease Analysis

A Python data analysis and visualization project that collects disease and COVID-19 data from WHO API and Worldometer, processes the data using Pandas, and presents insights through charts, maps, heatmaps, network graphs, and 3D visualizations.

## Overview

This project focuses on collecting, cleaning, analyzing, and visualizing global disease and COVID-19 data using Python.

The project uses disease indicators from the WHO API and COVID-19 statistics collected from Worldometer using web scraping techniques. The collected data is cleaned, processed, and organized using Pandas, then visualized using different Python visualization libraries.

The notebook also demonstrates several visualization techniques, including bar charts, heatmaps, choropleth maps, bubble maps, network graphs, image processing filters, and 3D point cloud analysis.

Some visualizations are based on real collected data, while others use sample or manually created datasets to demonstrate different data visualization techniques.

## Features

- Import and organize required Python libraries
- Fetch disease indicator data from WHO API
- Filter disease-related indicators such as HIV, malaria, tuberculosis, cancer, diabetes, hepatitis, influenza, and COVID-19
- Scrape COVID-19 country statistics from Worldometer
- Use both Requests/BeautifulSoup and Selenium for web scraping
- Clean and preprocess health-related datasets using Pandas
- Save structured data into CSV files
- Visualize COVID-19 deaths across selected countries
- Create global disease heatmaps
- Create bubble maps for disease distribution
- Build a network graph showing relationships between selected countries and diseases
- Calculate centrality values in the disease-country network
- Create choropleth maps using Plotly
- Apply basic image processing filters such as sharpening and edge detection
- Create 3D visualizations for disease case analysis

## Technologies Used

- Python
- Pandas
- Requests
- BeautifulSoup
- Selenium
- WebDriver Manager
- Matplotlib
- Seaborn
- Plotly
- NetworkX
- PyCountry
- CSV
- Regular Expressions
- Jupyter Notebook

## Project Workflow

1. Import the required libraries for data collection, web scraping, data processing, and visualization.
2. Collect disease indicator data from the WHO API.
3. Filter important disease indicators using selected keywords.
4. Scrape COVID-19 data from Worldometer.
5. Store the scraped data in structured DataFrames.
6. Clean numeric columns and remove unnecessary symbols.
7. Save cleaned data into CSV files.
8. Create different visualizations to explore health and disease patterns.
9. Build a network graph connecting selected countries and diseases.
10. Apply image processing filters to map images.
11. Create 3D visualizations to demonstrate disease case analysis.

## Visualizations Included

- COVID-19 total deaths bar chart for selected countries
- Global disease heatmap by death intensity
- World disease distribution bubble map
- US choropleth map
- Heatmap of disease deaths across countries
- Network graph of countries and important diseases
- Betweenness centrality analysis for the network graph
- Image processing comparison using original, sharpened, and edge detection filters
- 3D disease point cloud analysis

## Data Sources

- WHO API
- Worldometer COVID-19 data
- Manually created sample datasets for visualization practice

## Important Note

Some parts of this project use real collected data from online sources, while other parts use sample or manually created datasets to demonstrate visualization techniques.

This project is mainly created for learning and practicing:
- Data collection
- API usage
- Web scraping
- Data cleaning
- Data visualization
- Working with maps
- Network analysis
- 3D plotting
- Basic image processing

## Installation

To run this project, install the required Python libraries:

```bash
pip install pandas requests beautifulsoup4 selenium webdriver-manager matplotlib seaborn plotly networkx pycountry
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/Global-Health-Disease-Analysis.git
```

2. Open the project folder:

```bash
cd Global-Health-Disease-Analysis
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the notebook cells step by step.

## Project Files

```text
Global-Health-Disease-Analysis/
│
├── Global_Health_Disease_Analysis.ipynb
├── README.md
├── BIG_disease_data.csv
├── selenium_covid_data.csv
├── clean_disease_symptoms_data.csv
├── final_project_data.csv
├── Full_Health_Descriptions.xlsx
├── organized_disease_symptoms_report.xlsx
└── world_map.png
```

## Skills Practiced

Through this project, I practiced:

- Working with APIs
- Web scraping using BeautifulSoup
- Web scraping using Selenium
- Data cleaning using Pandas
- Handling CSV files
- Creating visualizations using Matplotlib and Seaborn
- Creating interactive maps using Plotly
- Building graphs using NetworkX
- Applying simple image processing techniques
- Creating 3D plots using Matplotlib

## Future Improvements

Possible improvements for this project include:

- Adding more countries and disease indicators
- Improving data cleaning steps
- Adding more interactive dashboards
- Automating the data collection process
- Using updated real-time health datasets
- Creating a Streamlit dashboard for better presentation

## Author

Created by Yasmin Badran

