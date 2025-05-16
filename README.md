# Financial Sentiment Analysis

This project analyzes financial news/articles to determine sentiment using machine learning techniques.

## Structure

- `Data_Collection.ipynb`: Collects financial data
- `Data_Cleaning.ipynb`: Cleans and prepares data
- `Exploratory_Analysis.ipynb`: Data visualization and insights
- `Model_Building.ipynb`: Trains ML models
- `images/`: Visual outputs
- `financial_data_cleaned.csv`: Cleaned dataset

## How to Run

```bash
# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook

## 🚀 Key Features

- **Data Preprocessing**:
  - Label encoding for categorical features (e.g., `Sentiment`)
  - TF-IDF vectorization for textual data
  - Handling class imbalance using **SMOTE** (Synthetic Minority Over-sampling Technique)

- **Machine Learning Models Evaluated**:
  - Logistic Regression (**65.16% accuracy**)
  - Decision Tree Classifier
  - Random Forest Classifier
  - Support Vector Machine (SVM)
  - Bernoulli Naive Bayes
  - K-Nearest Neighbors (KNN)

- **Model Evaluation Techniques**:
  - Accuracy score
  - Confusion matrix
  - Classification report
  - Cross-validation
  - Hyperparameter tuning using GridSearchCV
