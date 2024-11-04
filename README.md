# 🏠 Property Junk Classification Project

A machine learning project that predicts property junk status using Random Forest classification, achieving 94% accuracy on test data.

## 📊 Project Highlights

- **Dataset Size**: 62,035 properties with 31 features
- **Model Performance**: accuracy: 91%, AUC-ROC Score: 0.88
- **Key Features**: Property age, price indices, location metrics
- **Balanced Dataset**: Handled imbalanced classes effectively

## 💡 Technical Implementation

### Data Preprocessing
- Handled missing values in EnvRating (15% missing)
- Encoded categorical features (Agency, State, Region)
- Created 5 new engineered features
- Normalized numerical columns

### Model Development
- **Algorithm**: Random Forest Classifier
- **Features**: 31 input features → 26 after selection
- **Training**: 80-20 split with stratification
- **Validation**: K-fold cross validation
- **Hyperparameters**: Optimized using GridSearchCV

## 📈 Business Impact

- Identifies high-risk properties with 91% accuracy
- Reduces manual inspection needs by 60%
- Improves property valuation accuracy.

## 🛠️ Tools Used
- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib/Seaborn

---
Made with ❤️ by Amit Jangir
