# 🎨 Data Preprocessing on Anime Dataset 🌟  
This project showcases the application of advanced data preprocessing techniques on an anime dataset, emphasizing data imputation, cleaning, transformation, and visualization. The goal is to prepare the dataset for further analysis or machine learning applications. 🧹📊  

## 🚀 Features  
- **Comprehensive Data Cleaning**: Handling missing values, duplicates, and outliers.  
- **Advanced Imputation Techniques**: Multiple strategies to address missing data.  
- **Data Transformation**: Feature scaling, encoding, and normalization.  
- **Visual Insights**: Exploratory Data Analysis (EDA) using beautiful visualizations.  

---

## 📂 Dataset  
The dataset consists of information about popular anime, including attributes like genres, ratings, episodes, and user reviews. It serves as a perfect playground for applying preprocessing techniques.  

---

## 🛠️ Techniques Applied  

### 1. **Data Cleaning** 🧼  
- Handling missing values in critical features such as `rating`, `genre`, and `episodes`.  
- Removing duplicate and irrelevant rows/columns.  
- Identifying and addressing outliers using IQR and z-score methods.  

### 2. **Imputation Techniques** 🤔  
- **Mean/Median Imputation**: For numerical columns like `rating`.  
- **Mode Imputation**: For categorical columns like `genre`.  
- **K-Nearest Neighbors (KNN) Imputation**: Leveraging patterns in similar data points. 

### 3. **Feature Transformation** 🔄  
- **Encoding Categorical Features**: One-hot encoding and label encoding for columns like `genre` and `type`.  
- **Scaling and Normalization**: Min-Max scaling, standardization for columns like `rating`.  

### 4. **Data Visualization** 📊  
- **Correlation Heatmaps**: Visualizing relationships between features.  
- **Box Plots**: Identifying outliers in numerical features like `rating`.  
- **Bar Charts**: Comparing genres and their average ratings.  
- **Distribution Plots**: Understanding feature distributions post-transformation.  
---

## 🛠️ Tech Stack  
- **Python Libraries**:  
  - `pandas`, `numpy` – Data handling and cleaning.  
  - `scikit-learn` – Imputation and scaling.  
  - `seaborn`, `matplotlib`, `plotly` – Visualizations.  

---
