# 🇮🇩 Indonesian Worker Welfare Classification Model Using Clustering (Per Province Per Year)

This project focuses on analyzing the welfare of workers across Indonesian provinces by clustering regions based on key economic features, and building classification models to predict welfare classes. The project utilizes publicly available socio-economic data and aims to support regional labor policy insights using machine learning.

---

## 📊 Project Overview

This project performs the following key steps:

1. **Data Preprocessing**  
   - Source: Public socio-economic datasets (provided as CSV in this repository)
   - Features:  
     - Garis Kemiskinan (Poverty Line)  
     - Upah Minimum Provinsi (UMP - Provincial Minimum Wage)  
     - Rata-rata Penghasilan (Average Income)  
     - Upah Rata-rata (Average Wages)  
   - Yearly and provincial data normalization

2. **Unsupervised Clustering**  
   - Group provinces using clustering algorithms (e.g., KMeans)
   - Each cluster represents a "welfare class" label for supervised learning

3. **Supervised Classification**  
   - Train multiple classifiers to predict welfare class:
     - Logistic Regression
     - Random Forest
     - etc.
   - Evaluate and compare model performance using metrics like accuracy, precision, recall, F1-score.

---

## 🗂️ Project Structure

Indonesian-worker-welfare-classification-model-using-clustering-per-province-per-year/
│
├── data/
│ └── worker_welfare_dataset.csv # Initial dataset (per province, per year)
│
├── notebooks/
│ ├── 01-data-preprocessing.ipynb
│ ├── 02-clustering.ipynb
│ ├── 03-classification-models.ipynb
│
├── requirements.txt
├── README.md


---

## 🧠 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Indonesian-worker-welfare-classification-model-using-clustering-per-province-per-year.git
cd Indonesian-worker-welfare-classification-model-using-clustering-per-province-per-year
```

### 2. Install Dependencies
Make sure you have Python installed (recommended: version 3.9+). Then install required libraries:

pip install -r requirements.txt

### 3. Run the Notebooks
Launch Jupyter Notebook or VS Code and follow the analysis:

01-data-preprocessing.ipynb

02-clustering.ipynb

03-classification-models.ipynb

Each notebook is self-contained and includes detailed steps and explanations.

