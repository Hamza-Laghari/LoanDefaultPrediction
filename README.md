# Social Media Usage Analyzer

This project analyzes student social media usage patterns and predicts potential addiction levels using machine learning models. The aim is to provide insights into how different features like daily usage hours, sleep duration, and reasons for social media use affect overall student well-being.

---

## Dataset
The dataset includes:
- Student demographics
- Daily usage hours
- Sleep patterns
- Reasons for social media use
- Academic impact

---

## Data Preprocessing
1. **Handling Missing Values**: Checked and treated missing/null values in the dataset.  
2. **Encoding Categorical Features**: Converted categorical columns (like `REASON`) into numerical representations using Label Encoding.  
3. **Feature Scaling**: Standardized numerical features to bring them on a similar scale.  
4. **Train-Test Split**: Split the dataset into training and testing sets to evaluate model performance.  

---

## Models Trained
1. **Linear Regression**  
   - MSE: 0.80  
   - R²: 0.19  

2. **Random Forest Regressor**  
   - MSE: 0.46  
   - R²: 0.54  

Random Forest performed significantly better than Linear Regression for this dataset.

---

## Insights
- Random Forest is more effective in handling non-linear relationships in the data.  
- Features like daily usage hours and reasons for using social media strongly influence addiction scores.  

---

## Future Work
- Resampling techniques (to handle imbalance in target variable).  
- Hyperparameter tuning for Random Forest.  
- Exploring other ensemble models like XGBoost or Gradient Boosting.  

---

## Tech Stack
- **Python**
- **Pandas, NumPy**
- **Scikit-learn**
- **Matplotlib, Seaborn**

