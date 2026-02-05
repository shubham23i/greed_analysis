# Fear vs Greed Analysis

## Overview

This project analyzes how trader performance and behavior change under
different market sentiment regimes (Fear vs Greed) using historical
trading data and the Fear & Greed Index.

## Contents

-   Jupyter notebook with data preparation, analysis, and results
-   README.md with setup and usage instructions
-   summary.txt with a short write-up of insights and strategy
    recommendations

## Data

-   Historical trading data (PnL, trades, leverage, positioning)
-   Fear & Greed Index (daily sentiment)

Data is aligned by date and analyzed at a daily trader level.

## Requirements

-   Python 3.9+
-   pandas
-   numpy
-   matplotlib
-   scikit-learn

Install dependencies:

``` bash
pip install pandas numpy matplotlib scikit-learn
```

## How to Run

1.  Open the notebook:

``` bash
jupyter notebook
```

2.  Run all cells from top to bottom.

## Outputs

-   Charts and tables comparing Fear vs Greed
-   Trader segmentation and clustering results
-   Actionable strategy recommendations

## Notes

-   Raw data contains no missing values or duplicates
-   Any missing values appear only after aggregation and are handled
    explicitly
