# Trader Behavior Insights – Primetrade.ai Assignment

## Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear/Greed) 
and trader performance using:
1. Fear & Greed Index Data
2. Historical Trader Data

The analysis identifies how trading behavior profitability, trade size, and win rate varies between Fear and Greed market conditions.

## Google Colab Notebook
[Click here to view the notebook in Google Colab](https://colab.research.google.com/drive/1MuIODNY4X0fnHwl767cJALZhXKmyZePj?usp=sharing)

## Folder Structure
```bash
ds_Ashwini_Kumar_Mahawar/
├── notebook_1.ipynb # Main Google Colab notebook with EDA and insights
├── csv_files/ # Processed CSV files
│ ├── processed_sentiment.csv
│ ├── processed_trader_data.csv
│ └── merged_trader_sentiment.csv
├── outputs/ # Charts generated during EDA
│ ├── sentiment_distribution.png
│ ├── profitability_by_sentiment.png
│ ├── trade_size_by_sentiment.png
│ └── win_rate_by_sentiment.png
├── ds_report.pdf # Final report summarizing insights
└── README.md # Setup instructions and project notes
```

## How to Run
1. Open `notebook_1.ipynb` in Google Colab or use the above link.
2. Upload `fear_greed_index.csv` and `historical_data.csv` to the Colab environment.
3. Run all cells to:
   - Clean and preprocess the datasets
   - Merge trader and sentiment data
   - Perform EDA
   - Generate CSV outputs and charts
4. Review outputs in `csv_files/` and `outputs/` folders.
5. See final summarized insights in `ds_report.pdf`.

## Requirements
- Python 3.9+
- pandas
- matplotlib
- seaborn
- reportlab

## Author
**Ashwini Kumar Mahawar**
