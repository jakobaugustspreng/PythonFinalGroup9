# Fast Food Stock Market Performance Analysis

Welcome to the Final Project of the course **Python for Data Science**. It consists of analyzing the performance of 10 major fast-food companies in the stock market over the years and involves questions related to stock trends, trading volumes, price spreads, and other insights. 

## Dataset Overview

**Note**: *BRK-A is not a fast-food company, but following the given instructions of the project we included the dataset in our analysis.*


The dataset consists of stock market data for 10 fast-food companies, each stored in separate CSV files. Each file contains the following columns:

- **Date**: Trading date
- **Open**: Opening price
- **High**: Highest price during the session
- **Low**: Lowest price during the session
- **Close**: Closing price
- **Adj Close**: Adjusted closing price (dividends and splits)
- **Volume**: Number of shares traded during the session

### Companies Included:
1. **BRK-A**: Berkshire Hathaway Inc.
2. **DNUT**: Krispy Kreme, Inc.
3. **DPZ**: Domino's Pizza, Inc.
4. **LKNCY**: Luckin Coffee Inc.
5. **MCD**: McDonald's Corporation
6. **PZZA**: Papa John's International, Inc.
7. **QSR**: Restaurant Brands International, Inc.
8. **SBUX**: Starbucks Corporation
9. **WEN**: The Wendy's Corporation
10. **YUM**: Yum! Brands, Inc.

## Exercises and Deliverables

This project is divided into 10 exercises, each addressing specific aspects of stock performance analysis. Below is a summary of the tasks and their objectives:

### Exercise 1:
- Print the number of rows and columns for each dataset.
- Display column names and their data types.

### Exercise 2:
- Extract rows for the year 2023 and print the number of rows.
- Visualize the **Close price trend** for this period.

### Exercise 3:
- Find the day with the highest **Close price** for each company.
- Display the date alongside the price.

### Exercise 4:
- Group the data by month and calculate the **average Close price** for each company.
- Plot the monthly averages for 3 companies and provide a justification for the chosen chart.

### Exercise 5:
- Compute the **yearly average Close price** for each company.
- Plot a comparison of yearly averages across all companies with a justification.

### Exercise 6:
- Create a plot showing the **range of prices** (High-Low) for each month for every company.
- Justify the chosen chart.

### Exercise 7:
- Create a plot showing the relationship between **trading volume** and **Close price** for a selected company.
- Add insights and justify the chart selection.

### Exercise 8:
- Identify the month with the **highest total trading volume** for each company.
- Display the results in a summary table.

### Exercise 9:
- Merge datasets for all companies into a single dataset for each year.
- Print the structure of the combined dataset and ensure proper alignment and handling of missing values.

### Exercise 10:
- Calculate the **daily spread** (High-Low) for each company.
- Compute the **average spread** and visualize it in a chart, with justification.
- Interpret which companies exhibit the largest spreads and why.

## Project Goals

This project aims to:
- Extract meaningful insights from historical stock market data.
- Develop expertise in data preprocessing, visualization, and interpretation.
- Explore relationships between financial metrics and justify analytical decisions.
- Collaborate effectively using GitHub for version control and project management.

## How to Run the Project

Follow these steps to run the project:

1. Clone this repository:
   	```bash
   	git clone https://github.com/jakobaugustspreng/PythonFinalGroup9.git
   	cd jakobaugustspreng/PythonFinalGroup9

2. Install dependencies:
   	```bash
	pip install -r requirements.txt

3. Execute the analysis script:
	```bash
	python main.py

4. View the generated plots and summary results.

## License
This project is for educational purposes and does not include any proprietary or confidential data.


