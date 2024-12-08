# 📊 EDA and Feature Engineering of Google Play Store Dataset

---

## 📝 Problem Statement

> **"Discover trends, identify popular app categories, and analyze app performance using the Google Play Store Dataset!"**

With over **2.56 million apps**, the Play Store plays a huge role in our daily lives. The goal is to:

- Identify the **most popular category**.
- Find the app with the **largest number of installs**.
- Find the app with the **largest size**, and more!

---

## 📂 Dataset Overview

- **Rows:** 10,841  
- **Columns:** 20  
- **Key Columns:**  
  - `App`, `Category`, `Rating`, `Size`, `Installs`, `Price`, `Type`  

---

## 🛠️ Steps Followed

### **1. Data Cleaning**  
- Removed invalid values in `Reviews`.  
- Converted `Size` and `Price` to numeric formats.  

### **2. Exploratory Data Analysis (EDA)**  
- Identified **top categories** by number of apps.  
- Analyzed install trends by category.  

### **3. Feature Engineering**  
- Added `Day`, `Month`, and `Year` columns from the `Last Updated` feature.  

---

## 🔍 Key Insights

| **Feature**              | **Observation**                                                          |
|---------------------------|--------------------------------------------------------------------------|
| **Most Popular Category** | "Family" category has the most apps, followed by "Games".               |
| **Largest App Size**      | "Adobe Premiere Rush" has the largest size.                             |
| **Top Installed App**     | "Subway Surfers" leads the "Games" category with 1B+ installs.          |
| **Free vs Paid**          | 90% of apps are free; only 10% are paid.                                |
| **Highest Rated App**     | "CT Brain Interpretation" (Family Category) is the highest rated.       |

---

## 📈 Visualizations

### 🌟 **Most Popular App Categories**  
*(Add a visualization image or description here)*  

### 🔝 **Top 5 Apps by Installs (Games)**

| **App**           | **Installs** |
|--------------------|--------------|
| Subway Surfers    | 1B+          |
| Candy Crush       | 500M+        |

---

## 💾 Internal Assignments

1. Find categories with the **largest number of installations**.  
2. Identify **top 5 apps in each popular category**.  
3. Count apps with **5-star ratings**.  

---

## 🛠 Technologies Used

- **Python Libraries:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`  
- **Dataset Source:** [Google Play Store Dataset](https://raw.githubusercontent.com/krishnaik06/playstore-Dataset/main/googleplaystore.csv)  

---

## 🎯 Project Highlights

- Dataset cleaned and processed with advanced techniques.  
- In-depth analysis of app trends on Google Play Store.  
- Useful insights for app developers and marketers.  
