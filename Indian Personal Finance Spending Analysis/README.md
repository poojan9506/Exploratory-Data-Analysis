# 💰 Indian Personal Finance Spending Analysis

An Exploratory Data Analysis (EDA) project that looks at how Indian households earn, spend and save money. Built with Python, Pandas, NumPy, Matplotlib and Seaborn.

---

## 📌 Project Overview

Personal finance decisions depend on understanding where money actually goes. This project cleans a personal-finance dataset and explores it to answer questions such as:

- Which categories take the biggest share of monthly spending?
- How does spending change with income level?
- How much do people save, and what affects savings?
- Are there differences across city tiers, age groups or occupations?

> ✏️ **Edit this list** to match the exact questions your notebook answers.

---

## 🎯 Objectives

1. Load, inspect and clean the dataset (missing values, duplicates, data types, outliers).
2. Understand the structure of the data using descriptive statistics.
3. Visualise spending patterns across categories and demographics.
4. Find correlations between income, expenses and savings.
5. Summarise the key insights in plain language.

---

## 🗂️ Repository Structure

```
Exploratory-Data-Analysis/
└── Indian Personal Finance Spending Analysis/
    ├── data/            # dataset (CSV)
    ├── notebook.ipynb   # EDA notebook
    └── README.md        # project documentation
```

> ✏️ Replace the file names above with your actual ones.

---

## 📊 Dataset

| Item | Details |
|------|---------|
| Source | *(add Kaggle / other link here)* |
| Rows × Columns | *(add, e.g. 20,000 × 27)* |
| Type | Indian household / individual finance data |

**Key columns** *(update as per your data)*:

| Column | Description |
|--------|-------------|
| Income | Monthly income |
| Age / Occupation / City_Tier | Demographic details |
| Rent, Groceries, Transport, Eating_Out, Entertainment, Utilities, Healthcare, Education | Monthly spending by category |
| Savings / Desired_Savings | Actual and target savings |

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## 🔍 Methodology

1. **Data Loading:** read the CSV with Pandas.
2. **Data Cleaning:** handle nulls and duplicates, fix data types, treat outliers.
3. **Feature Engineering:** total expenses, savings rate (`savings / income`), expense share per category.
4. **Univariate Analysis:** distributions of income, expenses and age.
5. **Bivariate / Multivariate Analysis:** income vs expenses, category-wise spending by city tier, correlation heatmap.
6. **Insights:** summarised findings at the end of the notebook.

---

## 📈 Key Insights

> ✏️ Fill these with your real findings. Example format:

- Housing/rent and groceries make up the largest share of spending.
- Higher-income groups save a higher amount, but the savings *rate* differs by city tier.
- Discretionary spending (eating out, entertainment) rises faster with income than essentials.
- Income shows a strong positive correlation with total expenses and savings.

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/poojan9506/Exploratory-Data-Analysis.git
cd "Exploratory-Data-Analysis/Indian Personal Finance Spending Analysis"

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# 3. Launch the notebook
jupyter notebook
```

Then open the notebook and run all cells.

---

## 🔮 Future Improvements

- Build an interactive dashboard (Power BI / Streamlit).
- Add predictive modelling for savings.
- Add statistical hypothesis tests across groups.

---

## 👤 Author

**Poojan Desai**
Aspiring Data Analyst | B.E. Computer Engineering, Monark University

- GitHub: [github.com/poojan9506](https://github.com/poojan9506)
- LinkedIn: [linkedin.com/in/poojan-desai](https://linkedin.com/in/poojan-desai)
- Email: poojandesai06@gmail.com

⭐ If you found this project useful, consider giving it a star!
