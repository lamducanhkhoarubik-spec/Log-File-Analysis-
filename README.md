# Log File Analysis - 

This is my first ***Data Analysis** project for a common dataset: ***Log File***.
This project covers some fundamental skills: EDA Analysis, text processing (if using Pandas), Data Visualization, Polar.
Because of lack of time, this project was finished as an assignment, it should not be seen as an official materials for learning.


---

## 📖 1. Dataset
- The dataset [Online Shopping Store - Web Server Logs](https://www.kaggle.com/datasets/eliasdabbas/web-server-access-logs) has a capacity of 3.3 GB on Kaggle
- You can mitigate to 2 milion rows for good processing.

---

## 🧩 2. Polar description
### 🚀 High-Performance Log Analysis with Polars

This project demonstrates how to process and analyze massive server log files (3.3GB+) efficiently using **Polars**, a blazing-fast DataFrame library written in Rust.

### 📖 Overview
Processing large-scale logs often leads to memory crashes with traditional tools. By utilizing **Lazy Evaluation** and **Multi-threading**, this project extracts actionable insights (Security, Traffic, and Performance) from raw server data without exhausting system resources.



### ⚡ Key Features
- **Speed:** 10x-100x faster than Pandas for large-scale log parsing.
- **Memory Efficient:** Uses `scan_csv` (LazyFrame) to handle files larger than RAM.
- **Traffic Analysis:** Identifies "Bandwidth Monsters" and Top IP intruders.
- **Security Insights:** Analyzes 404 errors and suspicious User-Agents (Bots vs. Humans).
- **Visualization:** Beautifully rendered charts for Browser distribution and Traffic spikes.

---



