# Biostatistics-and-Ecological-Visualization-and-Analysis
# README

## Biostatistics and Ecological Statistics Visualization

### Description

This repository contains Python scripts and Jupyter Notebook examples for analyzing and visualizing biostatistics and ecological statistics datasets. The dataset used in this project includes information on temperature, pollution levels, and species population across various regions.

### Features

- **Data Loading and Overview**
  - Load and preview the dataset using pandas.
  - Analyze the structure and basic information of the dataset (e.g., number of rows, columns, and data types).

- **Descriptive Statistics**
  - Compute numerical columns' mean, median, min, and max values.

- **Data Visualization**
  - Histograms to analyze distributions of variables.
  - Boxplots to compare species population across regions.
  - Line plots to observe trends over time.
  - Heatmap to display correlation between numerical variables.

- **Regression Analysis**
  - Perform multiple linear regression to understand the relationship between variables.
  - Visualize regression results with scatter plots and regression lines.

- **Interactive User Interface**
  - Add new data rows using input widgets.
  - Delete rows based on their index.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/TanvirArefin/Biostatistics-and-Ecological-Visualization-and-Analysis.git

2. Navigate to the repository directory:

   ```bash
   cd Biostatistics-and-Ecological-Visualization-and-Analysis
3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt

- **Usage**
1. Run the Jupyter Notebook:

   ```bash
   jupyter notebook
Open the notebook file in your browser to execute the code.

2. Data Loading: Replace the dataset path in the pd.read_csv() function with the path to your local dataset.

3. Interactive Features:
   - Use the input widgets to add new data rows.
   - Enter an index and click the delete button to remove rows.

- **Example Dataset Columns**
  1. Timestamp: Date and time of data collection.
  2. Species: Name of the species.
  3. Region: Geographical region (e.g., Zone 1, Zone 2, Zone 3).
  4. Temperature (°C): Recorded temperature in degrees Celsius.
  5. Pollution_Level (ppm): Pollution level in parts per million.
  6. Species_Population: Population count of the species.

- **Example Visualizations**
  1. Histograms: Display temperature distributions, pollution level, and species population.
  2. Boxplots: Compare species population across different regions.
  3. Line Plots: Show trends in species population over time.
  4. Heatmap: Show correlations between variables.

- **Dependencies**
   ```bash
  import pandas as pd
  import numpy as np
  import matplotlib.pyplot as plt
  import seaborn as sns
  import statsmodels.api as sm
  import ipywidgets as widgets

## Author
### Tanvir Arefin

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to suggest changes or report problems.

## Acknowledgments
This project was created for educational purposes and demonstrates biostatistics and ecological data visualization techniques.
