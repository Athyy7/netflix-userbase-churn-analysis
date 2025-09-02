# Netflix Customer Churn Prediction

A machine learning project to analyze user behavior and predict customer churn for Netflix.  
The project uses the **Netflix userbase dataset** to identify patterns that contribute to customer churn and applies predictive models to estimate churn probability.

---

## 📌 Objectives

- Perform exploratory data analysis (EDA) on Netflix userbase data  
- Identify key features influencing churn (e.g., age, plan type, country, subscription length)  
- Build and evaluate machine learning models for churn prediction  
- Provide insights into churn drivers for potential business actions  


---

## 🧪 Methodology

1. **Data Preprocessing**
   - Handle missing values
   - Encode categorical features (e.g., country, plan type)
   - Scale numerical features (e.g., age, subscription length, monthly revenue)

2. **Exploratory Data Analysis**
   - Distribution plots of demographics and plan usage
   - Correlation analysis between features
   - Visualization of churn vs. non-churn groups

3. **Modeling**
   - Algorithms tested: Logistic Regression, Decision Tree, Random Forest, KNN, SVM  
   - Data split into training and test sets  
   - Evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

4. **Evaluation**
   - Compare model performance
   - Select best-performing model
   - Analyze feature importance

---

## ⚙️ Installation

### Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```


## 🚀 Usage

1. Clone this repository  
2. Open `Netflix_Userbase.ipynb` in Jupyter Notebook or Google Colab  
3. Run all cells to:
   - Load and preprocess the dataset  
   - Perform EDA with visualizations  
   - Train and evaluate churn prediction models  

---

## 📊 Results

### EDA Findings
- Certain demographics show higher churn probability  
- Plan type and subscription length are strong churn indicators  

### Model Performance
- Random Forest and SVM achieved the highest F1-scores  
- Feature importance highlighted subscription type, monthly revenue, and tenure as top predictors  
