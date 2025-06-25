## 🚗 Vehicle Insurance Claim Analysis

📊 **Exploratory Data Analysis | Claim Behavior Insights | Data Cleaning | Feature Distribution**

This repository presents an analytical deep dive into a real-world **vehicle insurance dataset** with over **380,000+ records**. The goal was to understand **factors influencing insurance claim responses**, clean the data, and visualize key insights.

---

### 🔍 Project Objectives

* Clean and prepare a large insurance dataset
* Analyze claim frequency patterns across customer demographics and vehicle attributes
* Identify relationships between features like `Vehicle_Age`, `Annual_Premium`, `Vehicle_Damage` and `Response`
* Use visualizations to communicate patterns effectively

---

### 🤖 Dataset Overview

* **Rows:** 381,109
* **Columns:** 12
* **Key Features:** Age, Vehicle\_Age, Damage History, Annual Premium, Policy Channel, Region Code, Vintage
* **Target Variable:** `Response` (1 = Interested in insurance, 0 = Not interested)

---

### 📉 Data Cleaning Performed

* Removed duplicate records
* Handled outliers in `Annual_Premium` using IQR
* Verified and confirmed absence of null values

---

### 📈 Key Visualizations & Insights

* **Histogram Distributions:** Age, Vintage, Annual Premium
* **Count Plots:** Response vs Gender, Vehicle Damage, Insurance History
* **Box Plots:** Age, Vintage, and Premium vs Response
* **Bar Charts:** Region-wise & Channel-wise average claim rates
* **Grouped Analysis:** Vintage grouped into quartiles to see claim interest across tenure

---

### 🌟 Key Findings

* Claim interest **increases** with **vehicle age**, especially for >2 years
* Users with **previous vehicle damage** show **higher claim probability**
* Males had slightly higher response rates than females
* Policy sales channels 152 & 26 were most common, but claim rates varied

---

### 🛠 Tools & Libraries

* `Python` | `Pandas` | `NumPy` | `Seaborn` | `Matplotlib`

---

### 🚀 Future Scope

* Build a **classification model** to predict `Response`
* Implement **feature engineering** (e.g., one-hot encoding for categorical data)
* Deploy a **Streamlit dashboard** for live interaction

---

### 📄 Project Files

* `Vehicle_Insurance.csv` *(original dataset)*
* `mini-project-2.ipynb` *(analysis notebook)*

---
### 🙌 Connect with Me

If you found this project useful, feel free to follow and star ⭐ this repo. Let’s grow together in the world of data!

\#DataAnalysis #InsuranceEDA #Python #Seaborn #ClaimPrediction
