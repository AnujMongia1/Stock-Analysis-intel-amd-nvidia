# Stock Analysis - Intel, AMD, and Nvidia

This project analyzes the stock data of three companies: **Intel**, **AMD**, and **Nvidia**. The goal of this project was to explore individual stock trends, and perform a comparative analysis to help investors make informed decisions.

## Project Overview

The analysis is divided into two parts:

1. **Individual Stock Analysis**: Evaluates each stock’s price movements and statistical trends.
2. **Comparative Stock Analysis**: Compares the stock performance of Intel, AMD, and Nvidia to identify patterns and trends across the companies.

### Data Sources

- **Intel Stock Data**: Available from March 17, 1980 to May 6, 2022.
- **Nvidia Stock Data**: Available from January 22, 1999 to May 6, 2022.
- **AMD Stock Data**: Available from March 21, 1983 to May 6, 2022.

You can find the dataset used in this analysis on Kaggle:

https://www.kaggle.com/datasets/elmartini/stock-prices-intel-nvidia-and-amd

## Analysis Details

### 1. Individual Stock Analysis

### Intel

- **Average Closing Price**: $14.79
- **Highest Closing Price**: $65.91
- **Lowest Closing Price**: $0.13
- **Volume**: 0 to 567 million shares
- **Standard Deviation**: High volatility observed.

### Nvidia

- **Average Closing Price**: $25.00
- **Highest Closing Price**: $333.66
- **Lowest Closing Price**: $1.62
- **Volume**: 1.97 million to 923 million shares
- **Standard Deviation**: Moderate fluctuations.

### AMD

- **Average Closing Price**: $16.10
- **Highest Closing Price**: $161.91
- **Lowest Closing Price**: $0.31
- **Volume**: 3,200 to 325 million shares
- **Standard Deviation**: Noticeable price changes.

### 2. Visual Analysis

- **Intel: There was a gradual increase over the years with some fluctuations.**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/432ffba1-bf38-423d-a0a1-daae985dc35a/874bda14-587f-46d0-adca-bb318aca12fe/image.png)

- **Nvidia: There were ups and downs in the overall trend but in the recent years there were notable spikes and dips.**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/432ffba1-bf38-423d-a0a1-daae985dc35a/972d29d1-5c38-4896-b690-81d8c1cf6f7d/image.png)

- **AMD: They had a very steady growth with unusual rapid appreciation.**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/432ffba1-bf38-423d-a0a1-daae985dc35a/e1c0dbb7-267d-4bee-957b-9d84273c984d/image.png)

### 3. Comparative Stock Analysis

### Return Percentage Comparison

This section of analysis compares the daily return percentage of all three stocks. The formula used to calculate return percentage:

Return Percentage=(Current price-Previous price)/(Previous price)×100

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/432ffba1-bf38-423d-a0a1-daae985dc35a/9a475426-c383-47f7-8ceb-75dbac127800/image.png)

### Combined Stock Data Visualization

A single graph was plotted for this section to compare the price movements of Intel, Nvidia, and AMD stocks over the years to visualize their performance

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/432ffba1-bf38-423d-a0a1-daae985dc35a/9638549a-9b73-44a6-a187-019505c30cac/image.png)

### Stock Price Change Over Time

1. **Intel**: 22889.102231447843 %
2. **Nvidia**: 49409.544008483565 %
3. **AMD**: 959.6276743539871 %

## Requirements

- Python 3
- Libraries: matplotlib, pandas, numpy

## References

- Some of the statistical concepts and their implementation in Python were adapted by a [Medium article](https://medium.com/analytics-vidhya/python-for-stock-analysis-fcff252ca559).
- **Dataset Source**: [Kaggle - Stock Prices Intel, Nvidia, and AMD](https://www.kaggle.com/datasets/elmartini/stock-prices-intel-nvidia-and-amd)
