# Liver Disease Prediction

## 📌 Project Overview
This project predicts the likelihood of liver disease using the **Indian Liver Patient Records** dataset.  
It demonstrates data preprocessing, exploratory data analysis (EDA), and machine learning classification models.

## 📂 Dataset
- Source: [UCI ML Repository / Kaggle - Indian Liver Patient Records](https://www.kaggle.com/datasets/uciml/indian-liver-patient-records)  
- The dataset includes demographic and medical information such as age, gender, enzyme levels, and more.

## ⚙️ Steps in the Notebook
1. **Dataset Setup**
   - Downloaded dataset from Kaggle  
   - Loaded into Pandas DataFrame  

2. **Exploratory Data Analysis (EDA)**
   - Checked for null values  
   - Explored distributions of numeric features (histograms)  
   - Visualized feature correlations (heatmap)  

3. **Data Preprocessing**
   - Encoded categorical variables  
   - Handled missing values  
   - Separated features (X) and target (y)  

4. **Model Building**
   - Implemented classification models for prediction (e.g., Logistic Regression, Random Forest, etc.)  
   - Evaluated models using accuracy and performance metrics  

## 🛠️ Installation & Requirements
To run the notebook, install the following dependencies:
```bash
pip install kaggle pandas numpy matplotlib seaborn scikit-learn
▶️ Usage
Clone this repository or download the notebook.

Set up Kaggle API credentials to access the dataset.

Run the cells in order to preprocess data, analyze, and build predictive models.

📊 Results
The notebook provides accuracy and performance metrics of different machine learning models.

Visualizations highlight feature importance and relationships.

🚀 Future Work
Improve model accuracy with hyperparameter tuning

Test deep learning models

Deploy as a web app for medical usage
