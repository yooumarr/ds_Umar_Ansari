# Analysis of Trader Behavior vs Bitcoin Market Sentiment

**Candidate:** Umar Ansari

---

## Project Overview

This project explores the relationship between trader behavior and Bitcoin market sentiment. Using historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index, the goal is to identify patterns in profitability, trade volume, and leverage under different market sentiment conditions. The insights obtained can help in designing smarter and more informed trading strategies.  

**Key objectives:**

1. Analyze how trading behavior aligns or diverges from overall market sentiment (Fear vs Greed).  
2. Identify hidden trends or signals that could influence trading strategies.  
3. Visualize and statistically evaluate patterns in profitability, volume, and leverage.  

---

## Repository Structure

The repository is organized as follows:

1. **notebook_1.ipynb** – Data loading, cleaning, and preprocessing of both trader and sentiment datasets.  
2. **notebook_2.ipynb** – Merging datasets, exploratory data analysis (EDA), visualization, and machine learning preparation.  
3. **csv_files/** – Processed CSV files for analysis, e.g., `merged_trader_sentiment.csv`.  
4. **outputs/** – Graphs and visualizations saved as PNG files, e.g., `profitability_vs_sentiment.png`.  
5. **ds_report.pdf** – Final summarized insights, interpretations, and conclusions.  
6. **README.md** – Project description, setup instructions, and Colab links.  

---

## Setup Instructions

1. Open notebooks in **Google Colab**.  
2. Ensure all CSV files are located in the `csv_files/` folder.  
3. Run **notebook_1.ipynb** first to clean and preprocess the datasets.  
4. Run **notebook_2.ipynb** next to merge datasets, perform EDA, generate plots, and extract insights.  
5. All plots will automatically be saved in the `outputs/` folder.  

---

## Google Colab Links

1. **Notebook 1:** [Open in Colab](https://colab.research.google.com/drive/1IBEWwbz3a-_H-E2TTR4k2Y5rc3vOyxWM?usp=sharing)  
2. **Notebook 2:** [Open in Colab](https://colab.research.google.com/drive/1azjMJw3LvUlHDm4l0qpbuHPLK_7puqle?usp=sharing)  


---

## Key Findings

1. Traders tend to take **higher-risk trades during Greed periods**, resulting in higher average profitability.  
2. During Extreme Fear periods, traders are **more cautious**, with lower leverage and smaller trade volumes.  
3. Statistical analysis confirms significant differences in profitability between Fear and Greed periods.  
4. Market sentiment can serve as a **signal to adjust trading strategies and risk management**.  

