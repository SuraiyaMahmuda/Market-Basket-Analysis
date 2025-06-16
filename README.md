# Market-Basket-Analysis

# 🛒 Market Basket Analysis using K-Means Clustering

## 📌 Objective
To segment customers based on purchasing behavior using **K-Means Clustering**, which helps in identifying groups of similar behavior for better marketing strategy.

---

## 📁 Data Source
**File Used:** `mall customers.csv`

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
  - `sklearn` (KMeans)

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
K-Means clustering successfully segmented customers, enabling businesses to create targeted and efficient marketing strategies based on income and spending behavior.
