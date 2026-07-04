# Coin Market Sentiment vs Trader Performance Analysis

## Project Overview

This project analyzes the relationship between the Coin Fear & Greed Index and historical trading activity. The objective is to determine whether market sentiment influences trader performance and trading behaviour by combining sentiment data with historical trade records.

## Objectives

* Compare trader performance during Fear and Greed market conditions.
* Analyze changes in trading behaviour across different sentiment states.
* Segment traders based on trading frequency and performance.
* Generate actionable strategy recommendations based on the analysis.

## Datasets

1. **Fear & Greed Dataset**

   * Daily Fear & Greed Index
   * Sentiment Classification
   * Sentiment Score

2. **Historical Trading Dataset**

   * Trade information
   * Position direction
   * Trade size
   * Fees
   * Closed PnL

## Methodology

1. Data loading and inspection
2. Data cleaning and preprocessing
3. Datetime conversion and alignment
4. Feature engineering
5. Daily trader-level aggregation
6. Merge trading data with sentiment data
7. Exploratory Data Analysis
8. Trader segmentation
9. Strategy recommendation

## Features Engineered

* Daily PnL
* Total Trades
* Winning Trades
* Win Rate
* Average Trade Size
* Total Trading Volume
* Total Fees
* Long Ratio
* Short Ratio
* Profit per Trade

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

## How to Run

1. Clone or download the project.
2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Place both CSV files in the project directory.
4. Open `Analysis.ipynb`.
5. Run all notebook cells from top to bottom.

## Outputs

The notebook generates:

* Summary tables
* Performance comparison charts
* Trading behaviour analysis
* Trader segmentation analysis
* Strategy recommendations

The generated figures are stored inside the **charts/** directory.
