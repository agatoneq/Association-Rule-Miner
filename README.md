
# 🛒 Association Rule Miner – Market Basket Analysis in Python

An interactive tool for association rule mining based on market basket data.  
Built with **Python**, using **ShinyLive** for real-time web-based visualization of discovered rules.

![image](https://github.com/user-attachments/assets/326afd0b-15fa-4bbd-84d5-d36a67c0e9be)
![image](https://github.com/user-attachments/assets/dff4ca66-90bf-408d-b48b-e49a5276b20c)


## 🧠 About the Project

- Applies **Apriori algorithm** to find frequent itemsets and generate association rules
- Designed for **educational and demonstrational** purposes
- Allows users to upload their own CSV datasets and dynamically explore results

## 📦 Features

- CSV upload of transaction data
- Data preview before processing
- Interactive support and confidence sliders
- Automatic generation of frequent itemsets
- Display of top N rules with lift, support, and confidence
- Visual rule listing with target item highlighting

## 📁 Files

- `app.py` – Main ShinyLive app file
- `foodmart.csv` – Example transaction dataset
- `foodmartDIFF.csv`, `xyz.csv`, etc. – Additional datasets
- `purchase_counts.csv` – Frequency summary
- `purchase_data.csv` – Pre-aggregated sample input

## ▶️ How to Run

You can run the app using **[ShinyLive](https://shinylive.io/py/)**:

1. Visit: [https://shinylive.io/py/](https://shinylive.io/py/)
2. Upload the contents of this repository
3. Open `app.py` in the interface
4. Run the application directly in your browser

> Alternatively, clone this repo and run locally with a Python + Shiny setup if available.

## 🚀 Technologies

- Python
- [ShinyLive for Python](https://github.com/posit-dev/py-shiny)
- Pandas
- CSV handling
- Basic HTML output formatting

## 💡 Future Ideas

- Rule graph visualization
- Advanced metrics (e.g., conviction, leverage)
- Rule filtering by item type
- Export rules as CSV

## 📜 License

Personal learning project – open for exploration and improvement.
