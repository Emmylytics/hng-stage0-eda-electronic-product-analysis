# 📊 HNG Stage 0 – EDA of Electronic Product Dataset

## 📌Project Overview
This project is part of the HNG Data Analytics Stage 0 task, where I performed exploratory data analysis (EDA) on an electronic product dataset to uncover patterns in distribution, availability, and pricing.

---
## 🎯 Objectives
The analysis is focused on answering the following key questions:
* How are products distributed across different categories?
* What is the distribution of product availability statuses?
* How do product prices vary across categories?
  
---
## 📁 Dataset Overview
The dataset contains 10,000+ product records with attributes such as:
* `Product Name` – Name of the product
* `Brand` – Manufacturer of the product
* `Category` – Product type grouping
* `Price (USD)` – Product price in dollars
* `Stock` – Available quantity
* `Availability Status` – Current stock status (e.g. In Stock, Out of Stock)
* `Size` – Product size specification
* `Color` – Product color
* `Description` – Brief product details (often unstructured)

---
## 🛠️ Tools & Techniques
* Microsoft Excel
* Pivot Tables
* Pivot Charts
* Data Cleaning & Formatting

---
## 🧹 Data Cleaning & Preparation
Before analysis, the dataset was cleaned and structured:
* Converted price column to proper numeric (USD) format
* Standardized availability values for consistency
* Identified inconsistencies in size formatting
* Reviewed data types across columns

---
## 🔍 Key Insights
* Balanced Product Distribution:
Products are evenly distributed across categories, indicating no strong dominance.
* Even Availability Spread:
Availability statuses are fairly balanced, with discontinued and out-of-stock items appearing slightly more frequently.
* Minimal Price Variation:
Average prices are closely clustered across categories, ranging from approximately $476 to $537.

---
## 📉 Limitations
* No date/time column, limiting time-based analysis
* Dataset includes mixed product categories beyond electronics
* Inconsistent formatting in some fields (e.g., size)
* Prices don't vary much, making it hard to group products into different price levels

---
## 📦 Deliverables
* Cleaned dataset
* Pivot tables and charts
* Data visualization slides (PDF)

---
## 🚀 Key Takeaway
This project demonstrates the ability to clean, analyze, and visualize data using Excel, while extracting meaningful insights from a structured dataset.

---
## 🔗 Acknowledgment
This project was completed as part of the HNG Internship Program (Data Analytics Track).

---
hng-stage0-eda-product-analysis/
│
├── data/
│   └── cleaned_dataset.xlsx
│
├── visuals/
│   └── charts.png
│
├── presentation/
│   └── eda_slides.pdf
│
├── README.md
