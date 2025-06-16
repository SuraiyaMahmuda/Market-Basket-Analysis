# Market-Basket-Analysis

## 📌 Objective
This project focuses on identifying customer segments based on purchasing patterns using **K-Means clustering**. By analyzing spending scores and annual incomes, it aims to support data-driven marketing strategies.

---

## 📁 Data Source
**File Used:** `mall customers.csv` (collected from kaggle)

**Features:**
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1–100)`

---

## 🛠️ Tools & Libraries
- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:**
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `sklearn` 

---

## 🔍 Methodology

1. **Data Loading & Exploration**
   - Loaded the CSV file and visualized data distributions.

2. **Data Preprocessing**
   - Converted `Gender` to numeric values.
   - Selected `Annual Income` and `Spending Score` for clustering.

3. **Optimal Cluster Selection**
   - Used the **Elbow Method** to determine the best value of `k`.

4. **Clustering**
   - Applied **KMeans** with `k = 5`.
   - Visualized clusters using scatter plots.

---

## 📊 Results

Identified **five distinct customer segments**:
- 💰 High Income & High Spending
- 💸 High Income & Low Spending
- 🧍 Average Income & Average Spending
- 🔥 Low Income & High Spending
- 📉 Low Income & Low Spending

Visualizations provided clear insights into customer behavior patterns.

---

## ✅ Conclusion
K-Means effectively segmented customers into five distinct groups. These insights can help businesses personalize marketing efforts and improve customer engagement.
