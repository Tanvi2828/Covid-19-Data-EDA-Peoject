# Covid-19-Data-EDA-Peoject

## Overview
This project provides an Exploratory Data Analysis (EDA) of COVID-19 data to uncover trends, patterns, and insights related to the pandemic. Using Python libraries like Pandas, NumPy, Matplotlib, and Seaborn, the project explores global data, including metrics like confirmed cases, deaths, recoveries, and regional statistics.

## Dataset
The dataset used is `country_wise_latest.csv`, which includes the following features:
- **Country/Region**: Country or region name.
- **Confirmed**: Total confirmed COVID-19 cases.
- **Deaths**: Total deaths due to COVID-19.
- **Recovered**: Total recoveries from COVID-19.
- **Active**: Active COVID-19 cases.
- **New cases**: Recently reported cases.
- **New deaths**: Recently reported deaths.
- **New recovered**: Recently reported recoveries.
- Additional calculated metrics such as:
  - Deaths / 100 Cases
  - Recovered / 100 Cases
  - 1-week change and % increase in cases.
  - WHO Region classification.

## Objective
The main goal is to:
- Understand the global impact of COVID-19.
- Analyze regional and country-level trends.
- Examine relationships between features (e.g., death and recovery rates).
- Identify key insights to guide further study or policymaking.

## Tools and Libraries
- **Python**: Core programming language for analysis.
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical computations.
- **Matplotlib** & **Seaborn**: For data visualization.
- **Jupyter Notebook**: For interactive exploration.

## Key Analyses Performed
1. **Loading and Cleaning Data**: 
   - Data inspection (`head`, `info`) and missing value analysis.
   - Removal of inconsistencies, if any.
   
2. **Descriptive Statistics**:
   - Summary of confirmed, active, recovered, and death cases globally and by region.

3. **Visualization**:
   - Bar plots, line charts, and heatmaps to highlight patterns.
   - Country-specific trends and comparisons between regions.

4. **Insights**:
   - Countries with the highest case and death rates.
   - Recovery trends across regions.
   - Correlations between new cases, recoveries, and death rates.

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/covid19-eda.git
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook covid19_EDA.ipynb
   ```

## Results
- Regional and country-level trends are visualized to facilitate better understanding of the pandemic.
- The analysis helps highlight critical factors influencing COVID-19 outcomes, such as healthcare capacity and policy responses.

## Future Work
- Integration with real-time datasets for updated analyses.
- Predictive modeling using machine learning to forecast future trends.
- Comparative analysis of different waves of the pandemic.

## Acknowledgments
The dataset is sourced from publicly available COVID-19 data repositories. This project aims to aid data-driven decision-making during health crises.
