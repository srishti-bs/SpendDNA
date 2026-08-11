
# SpendDNA – Personal Spending Behaviour Analyzer 

> A Python-based transaction analytics project that turns raw UPI transactions into meaningful spending patterns, anomalies, and spending archetypes.

---

## 📌 Project Overview

SpendDNA is a transaction analytics project inspired by the idea of a financial version of Spotify Wrapped.

The project analyses transaction data to answer questions such as:

- Where does most of the money go?
- Which vendors receive the most money?
- Which spending categories dominate?
- How does spending change month by month?
- At what time of the day do transactions occur?
- Which transactions are unusually large?
- What kind of spending behaviour does the user exhibit?

The core project is designed around the **Unlox Academy SpendDNA – Week 2 Minor Project** requirements, including data cleaning, vendor extraction, category classification, spending analysis, time-of-day analysis, anomaly detection, and spending archetype detection.

The project also includes an analysis using my own Google Pay transaction statement as an additional personal-data experiment.

---

## 🎯 Objectives

The main objectives of SpendDNA are:

1. Clean and standardise raw transaction data.
2. Extract meaningful vendor names from transaction descriptions.
3. Categorise transactions into spending categories.
4. Calculate total credits and debits.
5. Analyse spending across different categories.
6. Identify the top vendors.
7. Analyse monthly spending trends.
8. Analyse time-of-day spending patterns.
9. Detect unusually large transactions using z-scores.
10. Identify spending archetypes using quantitative rules.
11. Generate a clean, readable financial summary report.

---

## 📂 Project Structure

```text
SpendDNA/
│
├── SpendDNA.ipynb
├── README.md
└── screenshots/
    └── spenddna_output.png
