# Titanic Survival Prediction with XGBoost and Other Classifiers

This machine learning project aims to predict the survival of Titanic passengers using multiple classification algorithms, including XGBoost, KNN, Logistic Regression, Decision Tree, Random Forest, and SVM. The models are trained and evaluated using accuracy and classification report metrics.

## Project Description

In this project, the following steps are applied:

1. **Importing Libraries**:
   - Essential libraries for data processing, analysis, and model training are imported:
     - **Pandas** and **Numpy** for data manipulation
     - **Matplotlib** and **Seaborn** for data visualization
     - **Scikit-learn** and **XGBoost** for machine learning models

2. **Loading and Preparing Data**:
   - The Titanic dataset is loaded and initial exploration is done using methods like:
     - `head()` to preview the first few rows.
     - `info()` to get information about data types and missing values.
     - `describe()` to view summary statistics.
   - Features and target are separated into `X` and `y` respectively.

3. **Data Preprocessing**:
   - Missing values are handled for each column.
   - Categorical features are converted into numerical values using encoding techniques.
   - The dataset is then split into training and testing sets.

4. **Model Training**:
   - Various classification models are trained, including:
     - **K-Nearest Neighbors (KNN)**
     - **Logistic Regression**
     - **Decision Tree**
     - **Random Forest**
     - **Support Vector Machine (SVM)**
     - **XGBoost**
   
5. **Model Evaluation**:
   - The trained models are evaluated using **Accuracy** and **Classification Report**.
   - The classification report includes precision, recall, and F1-score metrics for each model.

6. **Results**:
   - The evaluation results for all models are displayed for comparison.

## Libraries Used
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn (KNN, Logistic Regression, Decision Tree, Random Forest, SVM)
- XGBoost
## How to Use
1. **Clone the repository**:
2. **Install required libraries**
3. 3. **Run the code**:
Open the `Titanic ship.ipynb` file in Jupyter Notebook and follow the steps for data preprocessing, model training, and evaluation.

## Contributing
If you would like to contribute to this project, please feel free to submit a pull request. All suggestions and improvements are welcome!

## How to Use
1. **Clone the repository**:
