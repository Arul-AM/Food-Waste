# 🍽️ Local Food Wastage Management System

## 📌 Project Overview

This project aims to reduce food wastage by connecting surplus food providers (e.g., restaurants, grocery stores) with NGOs or individuals in need. It features an interactive web app for food listing, claiming, and data-driven insights powered by SQL and Python.

---

## 🎯 Objectives

- Create a structured platform to manage surplus food distribution.
- Enable CRUD operations on food listings via an interactive Streamlit interface.
- Perform data analysis using SQL to extract meaningful insights.
- Visualize food trends, claim patterns, and provider contributions.

---

## 🛠️ Tech Stack

- **Frontend/UI**: Streamlit
- **Backend**: SQLite + Python
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Database**: Local SQL database (`food.db`)
- **Data Source**: CSV files for providers, receivers, food listings, and claims

---

## 📊 Dataset Description

1. `providers_data.csv` - Food contributors with contact and location details  
2. `receivers_data.csv` - NGOs or individuals who receive food  
3. `food_listings_data.csv` - Available food items with expiry, type, quantity  
4. `claims_data.csv` - Claim records with status and timestamps

---

## 📈 Features

- Exploratory Data Analysis (EDA) on all datasets
- 15+ SQL-based analytical queries (e.g., top contributors, demand analysis)
- Full-featured Streamlit web app:
  - Food filtering (by type, city, provider)
  - Claim status display
  - Real-time food listing updates
  - Direct contact interface for providers/receivers
  - CRUD operations

---

## 🚀 How to Run

1. Install required packages:
   ```bash
   pip install -r requirements.txt
