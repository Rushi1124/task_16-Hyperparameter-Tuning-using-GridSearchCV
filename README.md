# Titanic Hyperparameter Tuning using GridSearchCV

## Description
This project demonstrates **hyperparameter tuning** for a Random Forest model on the Titanic dataset using `GridSearchCV`. The workflow includes:  
- Data preprocessing (scaling numerical features, encoding categorical features) using `ColumnTransformer`  
- Combining preprocessing and model training in a **Pipeline**  
- Defining a **parameter grid** for Random Forest  
- Applying **GridSearchCV** with cross-validation to find the best hyperparameters  
- Comparing the tuned model performance with the default model  

This approach ensures **efficient model optimization**, avoids data leakage, and demonstrates industry-standard ML practices.

## Tools
- Python  
- Pandas, NumPy  
- Scikit-learn (`Pipeline`, `ColumnTransformer`, `GridSearchCV`, `RandomForestClassifier`)  

## Steps
1. Load dataset and inspect features  
2. Preprocess data: drop irrelevant columns, fill missing values, encode categorical variables, scale numerical features  
3. Create an ML pipeline combining preprocessing and classifier  
4. Split data into train and test sets (stratified)  
5. Define hyperparameter grid for Random Forest  
6. Apply GridSearchCV with 5-fold cross-validation  
7. Extract best parameters and train the tuned model  
8. Evaluate performance (Accuracy, Precision, Recall, F1-score)  
9. Compare tuned model vs default model  

## Deliverables
- Jupyter Notebook with GridSearchCV implementation  
- Best hyperparameters output  
- Performance comparison table (default vs tuned model)  

## Author
**Rushita Bhosale**
