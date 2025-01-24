# COVID-19 Analysis Project

This project aims to perform an in-depth analysis of the impact of COVID-19 on various countries, by comparing it with the economic data (GDP) and mobility trends. The goal is to identify patterns and correlations between COVID-19 cases, GDP, and mobility metrics such as retail and recreation activity.

## Project Structure


covid19_analysis/
├── covid19_analysis.ipynb   # Jupyter notebook containing the analysis and visualizations
├── data/                     # Folder containing the raw data files
│   ├── covid19_data.csv      # COVID-19 data (Confirmed, Deaths, Recovered, Active cases)
│   ├── gdp_data.csv          # GDP data for various countries
│   └── mobility_data.csv     # Mobility data showing changes in movement patterns         
└── README.md                 # Project overview (this file)

Dataset Information

COVID-19 Data (covid19_data.csv):
Contains country-wise data for COVID-19 metrics such as:
Confirmed cases
Deaths
Recovered cases
Active cases
New cases, deaths, and recoveries
Death rate, recovery rate, etc.

GDP Data (gdp_data.csv):
Contains GDP data for various countries including:
GDP (Nominal) for 2022
GDP growth
Population size
GDP per capita
Share of world GDP

Mobility Data (mobility_data.csv):
Contains mobility data, showing percentage changes in:
Retail and recreation activity
Grocery and pharmacy visits
Parks visits
Transit stations usage
Workplace attendance
Residential activity

Project Overview
This project explores how COVID-19 cases correlate with various factors like GDP and mobility. The analysis is performed using Jupyter notebooks and visualized using matplotlib and seaborn to better understand the relationships between the variables.
The following steps are performed in the analysis:

Data Preprocessing: Clean and merge COVID-19, GDP, and mobility datasets.
Exploratory Data Analysis (EDA): Generate visualizations for understanding the distributions and correlations.
Statistical Analysis: Identify correlations and patterns between COVID-19 data, GDP, and mobility.
3D Visualization: Create 3D scatter plots to compare GDP, mobility, and confirmed COVID-19 cases.

Prerequisites
Before running the project, ensure that you have the following Python libraries installed:
pandas
matplotlib
seaborn
numpy
You can install the required dependencies by running:

Clone this repository to your local machine:

git clone https://github.com/Jothireddy/covid19_analysis.git
Navigate into the project directory:


cd covid19_analysis
Open the analysis notebook:


jupyter notebook covid19_analysis.ipynb
Execute the code cells to perform the analysis and visualize the results.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Data sources: The datasets used in this project are publicly available and include COVID-19 data, economic data (GDP), and mobility data.
Special thanks to the authors of the libraries used in this project, including pandas, matplotlib, and seaborn.


### Steps Covered in the README:

1. **Project Overview**: What the project is about and its goal.
2. **Dataset Details**: Information on the datasets used for the analysis.
3. **Setup Instructions**: Steps for installing dependencies and running the project.
4. **Visualizations**: Mentions the types of visualizations produced in the analysis.
5. **License and Acknowledgments**: Acknowledges the authors of libraries and data sources.

Feel free to modify any sections based on the specific details of your project, especially the repository URL and dataset specifics.

Let me know if you need any changes or additions to this!













