# 🚌 DTC Bus Breakdown Analysis (April 2023 – October 2024)

This project investigates breakdown patterns in Delhi Transport Corporation (DTC) buses using real operational data. It includes data preprocessing, trend visualization, and machine learning models for predicting breakdowns and maintenance status.

---

## 🔍 Project Highlights

### ✅ Data Cleaning & Processing
- Parsed inconsistent date formats and standardized them
- Cleaned and renamed column headers
- Calculated downtime and removed anomalies (negative/zero values)

### 📈 Trend Analysis
- Breakdown trends by:
  - Month and year
  - Bus numbers
  - Routes
  - Locations
  - Time of day (hour-wise distribution)
- Identified peak breakdown periods (e.g., May–June 2023) and locations (e.g., Nehru Place)

### 🕒 Downtime Evaluation
- Compared single vs repeated breakdowns
- Visualized downtime distributions
- Highlighted standard vs complex repairs

### 🤖 Machine Learning Models
- **Linear Regression**  
  - Predicted downtime hours  
  - R² Score: ~0.10 (low performance)

- **Random Forest Regressor**  
  - Poor predictive performance (R² ≈ 0.00)

- **K-Nearest Neighbors Classifier**  
  - Achieved 100% accuracy on maintenance classification

- **Support Vector Machine Classifier**  
  - Also achieved 100% accuracy on maintenance classification

---

## 🛠 Technologies Used
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **scikit-learn (sklearn)**
- **Google Colab**
- **Excel for raw data**

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `DTC_Breakdown_Analysis.ipynb` | Main Colab notebook with code and visualizations |
| `DTC_DATAANALYSIS.pdf` | Full written report with observations and insights |
| `DTC_IMP.xlsx` | Raw dataset |
| `DATA_IMP_cleaned.xlsx` | Cleaned and processed dataset |

---

## 📌 Use Case

This project can help transport authorities:
- Predict and prevent breakdowns
- Prioritize buses for maintenance
- Improve overall fleet reliability

---

## Author
Aemen Parveen
M.sc Electronics
Jamia Millia Islamia


