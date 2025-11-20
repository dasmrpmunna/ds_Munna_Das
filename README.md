# Trader Behavior Insights — Assignment Submission  
**Candidate:** Munna Das  

This project analyzes how Bitcoin market sentiment (Fear–Greed Index) relates to trader performance using historical Hyperliquid trading data.  
All analysis, cleaning, merging, EDA, and feature creation were performed in Google Colab as requested.

---

## 📁 Project Structure

```
ds_Munna_Das/
├── notebook_1.ipynb # Main Colab notebook (all core work)
├── csv_files/ # All processed/intermediate CSV outputs
│ ├── merged_trades_sentiment.csv
│ └── trader_features.csv
├── outputs/ # Visual outputs, charts, and EDA images
│ ├── boxplot_pnl_by_sentiment.png
│ └── daily_avg_pnl.png
├── ds_report.pdf # Final summarized report (insights + findings)
└── README.md # Project documentation
```


---

## 🚀 How to Run (Google Colab)

1. Open **notebook_1.ipynb** in Google Colab.  
2. Upload the following files into Colab `/content/`:  
   - `historical_data.csv`  
   - `fear_greed_index.csv`  
3. Run all cells in order.  
4. Processed CSVs will appear inside the `csv_files/` folder.  
5. Generated graphs/figures will be saved inside the `outputs/` folder.

---

## 📊 Key Outputs

- **Merged dataset:**  
  `csv_files/merged_trades_sentiment.csv`

- **Per-trader features:**  
  `csv_files/trader_features.csv`  
  (includes metrics like total trades, total PnL, win rate, etc.)

- **EDA Visualizations:**  
  - `outputs/boxplot_pnl_by_sentiment.png`  
  - `outputs/daily_avg_pnl.png`
  
- **Final Report:**  
  `ds_report.pdf`  
  (Summarizes methods, insights, and recommendations)

---

## 📝 Summary of Work

- Cleaned and parsed timestamps from historical trading data  
- Merged sentiment and trading datasets on date  
- Performed exploratory analysis to study PnL patterns under different sentiment states  
- Created trader-level metrics (win rate, avg PnL, volatility)  
- Generated visual insights and documented findings  

---

## 👤 Candidate Information
Prepared by **Munna Das**  
For the position: **Junior Data Scientist – Trader Behavior Insights**

---

