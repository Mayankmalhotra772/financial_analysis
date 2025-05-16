# 💰 Financial Sentiment Analysis

This project analyzes financial news and articles to determine sentiment using various machine learning techniques.

---

## 🗂️ Project Structure

- `Data_Collection.ipynb`: Collects financial data
- `Data_Cleaning.ipynb`: Cleans and preprocesses raw data
- `Exploratory_Analysis.ipynb`: Performs data visualization and extracts insights
- `Model_Building.ipynb`: Trains and evaluates machine learning models
- `images/`: Contains visual outputs and plots
- `financial_data_cleaned.csv`: The final cleaned dataset used for modeling

---

## ⚙️ How to Run

```bash
# 1. Create a virtual environment
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate

# 2. Install required dependencies
pip install -r requirements.txt

# 3. Launch Jupyter Notebook
jupyter notebook
```

Open and run the notebooks in the following order:
1. `Data_Collection.ipynb`
2. `Data_Cleaning.ipynb`
3. `Exploratory_Analysis.ipynb`
4. `Model_Building.ipynb`

---

## 🚀 Key Features

### 🧹 Data Preprocessing
- Label encoding for the `Sentiment` column
- TF-IDF vectorization for text features
- Class imbalance handled using **SMOTE** (Synthetic Minority Over-sampling Technique)

### 🧠 Machine Learning Models Evaluated
- **Logistic Regression** (**Achieved 65.16% accuracy** ✅)
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- Bernoulli Naive Bayes
- K-Nearest Neighbors (KNN)

### 📊 Model Evaluation Techniques
- Accuracy score
- Confusion matrix
- Classification report
- Cross-validation
- Hyperparameter tuning using GridSearchCV

---

## 📈 Results

- The best-performing model was **Logistic Regression**, which achieved an accuracy of **65.16%** on the test set.
