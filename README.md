```markdown
# 📈 Data Science Assignment – Trader Behavior & Market Sentiment Analysis

## 📂 Project Structure

```

ds_<your_name>/
├── notebook_1.ipynb
├── notebook_2.ipynb (optional)
├── csv_files/
│   ├── historical_data.csv
│   ├── fear_greed_index.csv
├── outputs/
│   ├── visualization_1.png
│   ├── visualization_2.png
│   ├── visualization_3.png
├── ds_report.pdf
└── README.md

```

## 📌 Overview  
This project analyzes the relationship between **crypto trader behavior** and **Bitcoin market sentiment** (Fear/Greed Index).  

The objective is to identify patterns in:

- Profitability  
- Leverage usage  
- Trading volume  
- Buy/Sell behavior  
- Risk-taking tendencies  

…and understand how these metrics shift during **Fear**, **Greed**, and **Neutral** market conditions.

---

## 📊 Datasets Used  

### 1. **Hyperliquid Historical Trader Data**  
Contains execution-level trading activity, including:  
- Account  
- Coin/Symbol  
- Size (Tokens & USD)  
- Side  
- Closed PnL  
- Fees  
- Timestamps  
- Position direction  

### 2. **Bitcoin Fear & Greed Index**  
Includes:  
- Timestamp  
- Sentiment value  
- Classification (Fear, Greed, Neutral, etc.)

Both datasets were cleaned and merged based on timestamp alignment.

---

## 🚀 How to Run This Project  

1. Open **notebook_1.ipynb** in **Google Colab**  
2. Place the CSV files inside the `csv_files/` folder  
3. Ensure correct paths when loading data  
4. Run all cells sequentially  
5. Visual outputs will be saved inside the `outputs/` directory  
6. The final insights summary is provided in `ds_report.pdf`

---

## 🧪 Techniques & Methods Used  

- Data Cleaning & Preprocessing  
- Missing Value Handling  
- Timestamp Parsing & Alignment  
- Merging Multi-Source Data  
- Feature Engineering (PnL flags, volume measures, leverage signals)  
- Sentiment Grouping  
- Statistical & Visual Trend Analysis  
- Interpretation of Market Behavior Patterns  

---

## 📘 Deliverables  

✔ Cleaned datasets  
✔ Merged analysis-ready dataframe  
✔ Exploratory Data Analysis (EDA)  
✔ Multiple visualizations  
✔ Final Report (`ds_report.pdf`)  
✔ Structured GitHub repository following assignment standards  

---

