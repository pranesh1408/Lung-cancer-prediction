
# **Lung Cancer Survival Prediction**  

### **Overview**  
This project analyzes lung cancer patient data to predict survival outcomes using machine learning. The dataset includes demographic, clinical, and treatment-related features for 890,000 patients.  

### **Key Features**  
- **Data Preprocessing**: Handled categorical variables, calculated treatment duration.  
- **Exploratory Data Analysis (EDA)**: Visualized survival rates by gender, smoking status, and cancer stage.  
- **Machine Learning Models**:  
  - **Logistic Regression**: 77.89% accuracy (baseline).  
  - **Gradient Boosting**: Identified key predictors (treatment duration, BMI, cholesterol).  
- **Challenges**: Class imbalance (78% non-survival), weak feature correlations.  

### **Results**  
- Models struggled due to imbalanced data (always predicting non-survival).  
- **Top Predictors**:  
  - Treatment duration (most important in boosting model).  
  - Hypertension & surgery (positively correlated with survival).  
  - Other cancers (negatively correlated).  

### **Future Improvements**  
- Address class imbalance (SMOTE, class weights).  
- Try survival analysis models (Cox Proportional Hazards).  
- Feature engineering for non-linear relationships.  

### **How to Run**  
1. Install dependencies:  
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn
   ```  
2. Run the Jupyter notebook (`Lung_Cancer_Prediction.ipynb`).  

### **Dataset**  
[Download here](https://www.kaggle.com/datasets/khwaishsaxena/lung-cancer-dataset) (replace with actual source).  

---  
**Note**: This is a simplified version. For detailed analysis, check the full notebook.
