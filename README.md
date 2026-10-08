# Shopify Stock Data Understanding, Cleaning & Exploratory Analysis

##  Project Overview

This project focuses on understanding, cleaning, and analyzing **Shopify stock market data** using Python and Pandas.

The analysis includes cleaning stock price attributes, calculating daily price changes and returns, analyzing trading volume, identifying unusual trading days, and summarizing stock return statistics.

##  Objectives

* Load and understand Shopify stock data.
* Clean stock price and volume attributes.
* Calculate daily price delta.
* Calculate daily percentage return.
* Analyze trading volume trends.
* Identify anomalous high-volume trading days.
* Calculate mean, variance, and standard deviation of daily returns.
* Perform basic exploratory data analysis.

##  Technologies Used

* Python
* Pandas
* Matplotlib
* Google Colab
* CSV Dataset

##  Dataset Attributes

The dataset contains the following important columns:

| Column         | Description                       |
| -------------- | --------------------------------- |
| `date`         | Stock trading date                |
| `open`         | Opening stock price               |
| `high`         | Highest price of the day          |
| `low`          | Lowest price of the day           |
| `close`        | Closing stock price               |
| `adj_close`    | Adjusted closing price            |
| `volume`       | Number of shares traded           |
| `Daily_Delta`  | Difference between Close and Open |
| `Daily_Return` | Daily percentage return           |

##  Data Cleaning

The following operations are performed:

1. Date values are converted into the proper date format.
2. Stock price attributes are converted into numeric values.
3. Missing values are checked and cleaned.
4. Dataset is sorted according to date.
5. Duplicate or invalid records can be removed when required.

##  Daily Price Delta

Daily price delta is calculated using:

```text
Daily_Delta = Close - Open
```

A positive value means the closing price is higher than the opening price.

A negative value means the closing price is lower than the opening price.

##  Daily Percentage Return

Daily return measures the percentage change in the closing price.

```text
Daily Return =
((Current Close - Previous Close) / Previous Close) × 100
```

This helps understand daily stock price movements.

##  Trading Volume Analysis

Trading volume is analyzed to understand how actively the stock was traded.

A **20-day moving average of volume** is also calculated:

```text
Volume_MA_20 = 20-day average trading volume
```

The daily volume and moving average are plotted to identify changes in trading activity.

##  Anomalous Trading Days

Unusually high-volume days are identified using a simple statistical rule:

```text
Volume > Mean Volume + 2 × Standard Deviation
```

These days are treated as anomalous trading days for exploratory analysis.

##  Return Statistics

The following statistics are calculated for `Daily_Return`:

* **Mean** – Average daily return
* **Variance** – Measures the spread of returns
* **Standard Deviation** – Measures the variability of daily returns

These statistics help understand the distribution and variability of Shopify stock returns.

##  Visualizations

The project includes:

* Trading volume trend
* 20-day volume moving average
* Daily return histogram
* Daily return distribution analysis

##  Project Workflow

```text
Load Shopify Dataset
        ↓
Understand Dataset
        ↓
Clean Data
        ↓
Convert Date and Numeric Columns
        ↓
Calculate Daily Delta
        ↓
Calculate Daily Return
        ↓
Analyze Trading Volume
        ↓
Calculate 20-Day Volume Average
        ↓
Identify Anomalous Trading Days
        ↓
Calculate Return Statistics
        ↓
Create Visualizations
        ↓
Final Exploratory Analysis
```

##  How to Run

1. Open **Google Colab**.
2. Upload the Shopify stock CSV file.
3. Import Pandas and Matplotlib.
4. Run the data cleaning code.
5. Run the analysis codes step by step.
6. View the statistics and visualizations.

## Plot Overview

<img width="1249" height="594" alt="Screenshot 2026-09-23 200339" src="https://github.com/user-attachments/assets/ccd45e98-24c8-48bc-b7f6-30cc8978d4a2" />

<img width="1075" height="595" alt="Screenshot 2026-09-23 200325" src="https://github.com/user-attachments/assets/b43331b1-b358-4ec3-af95-f26841aeb401" />




##  Conclusion

This project demonstrates basic **stock data understanding, cleaning, and exploratory analysis** using Python. It analyzes Shopify's daily price movements, returns, trading volume, and unusual trading activity using statistical methods and visualizations.

##  Author

**Vijaya lakshmi K**

BCA Student
