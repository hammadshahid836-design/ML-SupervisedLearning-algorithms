# Supervised Learning Projects

A collection of Jupyter notebooks applying supervised machine learning algorithms — **regression** and **classification** — to real-world datasets using **Scikit-learn**, **Pandas**, and **Seaborn**.

## 📁 Notebooks

| Notebook | Task | Description |
|---|---|---|
| [`linear_regression_marketing_revenue.ipynb`](notebooks/linear_regression_marketing_revenue.ipynb) | Regression | Predicting revenue from marketing spend and visitor data. Covers EDA, outlier removal, pairplots, and Linear/Ridge/Lasso regression models. |
| [`logistic_regression_loan_predictor.ipynb`](notebooks/logistic_regression_loan_predictor.ipynb) | Classification | Predicting loan approval ("Good Loan") using logistic regression. Covers data cleaning, categorical feature encoding (one-hot), and baseline dummy classifiers. |
| [`gene_expression_classification.ipynb`](notebooks/gene_expression_classification.ipynb) | Classification | Applying ML to gene expression data (PRAD dataset) — covers the full workflow from data import and preprocessing to modeling on high-dimensional biological data. |

## 🛠️ Tech Stack

- **Python 3**
- **Pandas / NumPy** — data loading and preprocessing
- **Matplotlib / Seaborn** — exploratory data analysis and visualization
- **Scikit-learn** — model building (Linear Regression, Ridge, Lasso, Logistic Regression, Dummy Classifier) and evaluation metrics

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/supervised-learning-projects.git
   cd supervised-learning-projects
   ```

2. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Launch Jupyter and open any notebook:
   ```bash
   jupyter notebook
   ```

> **Note:** Some notebooks were originally run in Google Colab and reference Google Drive paths (`/content/drive/...`) or local CSV files. Update these paths to point to your own copies of the datasets before running.

## 📌 Workflow Covered

Each notebook generally follows the same supervised learning pipeline:
1. **Data import** — loading raw CSV data
2. **EDA & cleaning** — handling nulls, checking data types, removing outliers
3. **Visualization** — pairplots, boxplots, count plots to understand feature relationships
4. **Feature engineering** — encoding categorical variables (one-hot encoding)
5. **Modeling** — fitting regression/classification models with Scikit-learn
6. **Evaluation** — assessing model performance with relevant metrics

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
