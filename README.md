# 🏨 Hotel Booking Analytics: Understanding Revenue Drivers & Customer Behaviour

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-3F4F75?logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Viz-4C72B0)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

> **Note:** *"DreamDest"* is a fictional company name used to frame this analysis in a real-world business context. The dataset is publicly available and does not represent any real organisation.

---

## 📌 Project Overview

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on a dataset of 66,541 international hotel bookings spanning 10 years (2010–2019). The analysis is framed around a fictionalised online travel agency, **DreamDest**, to simulate a real business analytics scenario.

The goal is to uncover actionable insights around revenue drivers, customer behaviour, seasonal patterns, discount strategy, and destination performance — the kind of analysis that directly informs business decisions.

---

## 🎯 Business Problem

DreamDest's leadership has raised the following concern:

> *"We have years of booking data but limited visibility into what's actually driving revenue and profit. We don't know which customer segments are most valuable, which destinations perform best, or whether our discount strategy is helping or hurting margins."*

### Key Business Questions

| # | Question | Stakeholder |
|---|----------|-------------|
| 1 | Which origin markets and destinations drive the most bookings and revenue? | Marketing & Sales |
| 2 | What does the typical DreamDest customer look like? | Product & CX |
| 3 | How have bookings and revenue trended over time? | Executive Leadership |
| 4 | What is the relationship between discounts and profit margins? | Finance |
| 5 | Which hotel ratings and booking durations are most associated with higher revenue? | Partnerships |

---

## 📊 Dataset

| Attribute | Detail |
|-----------|--------|
| Source | Publicly available hotel bookings dataset |
| Records | 66,541 bookings |
| Period | January 2010 – September 2019 |
| Currency | Singapore Dollar (SGD) |
| Missing Values | None |

### Key Features

- **Customer info** — Age, Gender, Origin Country, State, Location
- **Trip info** — Destination Country/City, Check-in/out Dates, No. of Days, No. of People
- **Hotel info** — Hotel Name, Hotel Rating, Rooms
- **Financial info** — Booking Price (SGD), Discount, GST, Profit Margin
- **Payment info** — Payment Mode, Bank Name

---

## 🔍 Analysis Structure

1. **Business Problem Definition** — Stakeholder questions and success criteria
2. **Data Loading & Quality Check** — Missing values, duplicates, data types
3. **Data Cleaning & Feature Engineering** — Date parsing, revenue/profit calculations, age bands
4. **Exploratory Data Analysis**
   - Customer Demographics
   - Origin Market Performance
   - Destination Analysis + Interactive World Map
   - Booking Trends Over Time (2010–2019)
   - Revenue & Pricing Analysis
   - Discount Strategy vs. Profit Margin
   - Hotel Quality & Length of Stay
   - Payment Method Analysis
   - Correlation Analysis
5. **Conclusions & Business Recommendations**

---

## 💡 Key Findings

- **Thailand, Malaysia, and Singapore** account for over 54% of all bookings — the top retention priority for marketing
- The **46–60 age group** generates the highest average booking value, making them the most valuable customer segment
- Bookings have grown **consistently year-on-year**, with a notable acceleration from 2016 onward
- **February, June, and November** are the lowest booking months — ideal windows for targeted promotions
- Discounts above **15%** measurably erode profit margins — recommending a discount cap for standard campaigns
- Hotels rated **4.5 and above** are associated with higher revenue per booking, supporting a premium partnership strategy
- **Iran, Kenya, Brazil, and Japan** significantly underperform as destinations compared to peers — growth opportunity

---

## 🛠️ Tech Stack

```python
pandas       # Data manipulation
numpy        # Numerical operations
matplotlib   # Static visualisations
seaborn      # Statistical plots
plotly       # Interactive charts & world map
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/BenaData/Hotel-Bookings-Data-Analytics.git
cd Hotel-Bookings-Data-Analytics
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn plotly
```

### 3. Launch the notebook
```bash
jupyter notebook hotel_bookings_professional_eda.ipynb
---

## 📈 Business Recommendations Summary

| Area | Recommendation |
|------|---------------|
| Marketing | Loyalty programmes targeting Thailand & Malaysia customers |
| Targeting | Premium offers for the 46–60 age segment |
| Seasonality | Flash promotions in Feb, Jun & Nov to fill booking gaps |
| Finance | Cap standard discounts at 15% to protect margins |
| Partnerships | Prioritise hotels rated 4.5+ for supply partnerships |
| Growth | Investigate underperforming destinations (Iran, Kenya, Brazil, Japan) |
| Payments | Introduce credit card co-branded rewards to lift booking value |

---

## 👤 Author

**Benard Mwinzi**  
Data Analyst | Python · SQL · Data Visualisation  
[![GitHub](https://img.shields.io/badge/GitHub-BenaData-181717?logo=github&logoColor=white)](https://github.com/BenaData)

---

*This project was built as part of a data analytics portfolio to demonstrate end-to-end EDA skills, business thinking, and data storytelling.*
