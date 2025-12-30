# 📊 Campaign to Pipeline Analytics

## Overview
This project analyzes marketing campaign performance across the sales funnel to understand which campaigns **actually drive revenue**, not just leads or pipeline volume.

The analysis focuses on win rate, deal size, sales velocity, and funnel progression to connect campaign activity to real business outcomes.

---

## 🔍 Questions Answered
- Which campaigns have the highest win rates?
- Which campaigns generate larger deals?
- Which campaigns move fastest through the funnel?
- How does performance differ by sales motion?
- Where do deals stall in the funnel by campaign?

---

## ⚙️ What This Notebook Does
- Loads and cleans campaign-to-opportunity data  
- Filters to relevant (late-stage or closed) deals  
- Calculates win rates, deal size, and sales cycle time by campaign  
- Compares campaign performance across different sales motions  
- Identifies funnel stages where deals commonly stall  
- Summarizes insights and business recommendations  

Each code block includes a short explanation of what is happening.

---

## 🛠 Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## ▶️ How to Run
```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook Campaign_to_Pipeline_Analytics_FULL.ipynb
