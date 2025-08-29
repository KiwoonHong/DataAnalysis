# DataanAnalysis

## Machine Learning Projects

## 1. Data Preparation
- Data Collection & Integration: Merge data from multiple sources
- Data Exploration & Quality Check: Missing values, outliers, data types, distribution checks

## 2. Data Splitting
- X-Y Split, Train/Test Split
- Perform early to prevent data leakage

## 3. Data Preprocessing (fit on train → transform on test)
- Missing Value Handling: Mean, Median, Model-based imputation
- Outlier Handling: Removal, Winsorization, Log transform
- Transformation: Log, Box-Cox, Square-root transforms
- Categorical Encoding: One-Hot, Target Encoding, Label Encoding
- Scaling / Normalization: StandardScaler, MinMaxScaler, RobustScaler

## 4. Feature Engineering
- Derived Features: e.g., Date → Day of week, Weekend flag
- Interaction Features: Multiplication, Summation of variables
- Domain Knowledge Features

## 5. Feature Selection / Dimensionality Reduction
- Statistical Methods: Remove low-variance or highly correlated features
- Model-based Methods: Tree-based feature importance, Lasso regression
- Dimensionality Reduction: PCA, LDA

## 6. Sampling (if needed)
- Class Imbalance Handling: Over/Under-sampling, SMOTE
- Apply only to training data, keep test data original

## 7. Model Training & Hyperparameter Tuning
- Model Training: Train data only
- Hyperparameter Tuning: GridSearchCV, RandomizedSearchCV, Bayesian Optimization

## 8. Model Evaluation
- Evaluate on validation sets
- Use test set only once for final performance evaluation

## 9. Pipeline Integration & Automation
- Use scikit-learn Pipeline, ColumnTransformer for consistent workflow
- Ensure reproducibility, maintainability, and easy deployment

