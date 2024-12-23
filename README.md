# Facebook-Stock-Data-Analysis

This project provides an end-to-end analysis of historical Facebook stock data, with a focus on exploratory data analysis (EDA), data preprocessing, visualization, and feature engineering. The objective is to derive insights into stock performance and trading trends that can be useful for traders and analysts.

## Introduction
The Facebook Stock Data Analysis notebook aims to analyze the historical stock data of Facebook (Meta). The analysis covers the following:

- Exploratory Data Analysis (EDA): Summarizes statistics, checks for missing data, and explores feature relationships.
- Data Visualization: Visualizes trends, distributions, and stock activity.
- Feature Engineering: Derives new features such as daily price change and high-low spread for enhanced analysis.
- Insights and Observations: Offers actionable insights based on the data.

## Installation
To run this project locally, follow these steps:

Clone the repository:

```bash
git clone https://github.com/danaelshrbiny10/Facebook-Stock-Data-Analysis.git
```
## Usage
To run the notebook, follow these steps:

1. Open the notebook in Jupyter or any preferred Python environment.

```bash
jupyter notebook facebook_stock_analysis.ipynb
```
2. Review the analysis and visualizations.
3. Modify the notebook to load your own stock data.

## Key Components

`Data Loading and Preprocessing`
- Objective: Load historical Facebook stock data and prepare it for analysis.
- Actions:
    - The dataset is loaded into the notebook.
    - The Date column is split into Day, Month, and Year for better analysis and visualization.

`Exploratory Data Analysis (EDA)`
- Objective: Understand the data through summary statistics and correlation analysis.
- Actions:
    - Generated summary statistics to explore the distribution of numerical features.
    - Checked for missing values and ensured data quality.
    - Created a correlation matrix to examine relationships between different features (e.g., Open, Close, High, Low).
      
`Data Visualization`
- Objective: Visualize trends, distributions, and key stock metrics.
- Actions:
    - Box Plots: Identified outliers for numerical features.
    - Line Plots: Visualized stock trends over time, including Open and Close prices.
    - Volume Trends: Analyzed trading volume trends.
    - Histograms: Explored the distribution of features.

`Feature Engineering`
- Objective: Create new derived features for further analysis.
- Actions:
    - Daily Price Change: Calculated as Close - Open for each day.
    - High-Low Spread: Calculated as High - Low for each day.

`Insights and Observations`
- Objective: Summarize key findings from the EDA and visualizations.
- Actions:
    - Identified trends in stock prices and trading volume.
    - Detected outliers and understood their potential impact.
    - Observed correlations between key features (e.g., Open and Close prices).
 
## Project Screenshots

Below are screenshots demonstrating key parts of the project:

| Screenshot | Description |
|------------|-------------|
| ![Screenshot from 2024-12-23 06-39-09](https://github.com/user-attachments/assets/0f49387c-b0d4-4415-83e6-83919c6bbab9) | **Line Plots**: Showed stock trends over time (Open and Close prices).|
| ![Screenshot from 2024-12-23 06-37-27](https://github.com/user-attachments/assets/461dc885-97b5-4c12-8c12-df218ee0e0f8) | **Box Plot**: Visualized numerical features to detect outliers.|
| ![Screenshot from 2024-12-23 06-40-50](https://github.com/user-attachments/assets/58df6d34-047a-44d7-8dc4-2002794ad45c) | **Volume Trends**: Analyzed trading activity.|
| ![Screenshot from 2024-12-23 06-44-24](https://github.com/user-attachments/assets/9b1fda94-93cc-4730-8870-af1beadb2c83) | **Histograms**: Explored the distribution of features.|


## License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
