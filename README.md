# Simple Linear Regression – Marketing ROI Analysis

## 📊 Project Overview

This project performs **Simple Linear Regression** analysis on a marketing dataset to understand the relationship between different marketing channels (TV, Radio, Social Media) and **Sales**. The goal is to identify the most effective channel and provide data-driven recommendations for marketing budget allocation and ROI optimization.

### Objectives:
- Explore and clean the marketing dataset
- Perform Exploratory Data Analysis (EDA)
- Build and evaluate a Simple Linear Regression model using `statsmodels`
- Validate model assumptions (Linearity, Normality, Homoscedasticity)
- Interpret results in business context
- Provide clear ROI-based marketing recommendations

---

## 🛠 Technologies Used

- **Python** 3.x
- **pandas** – Data manipulation
- **numpy** – Numerical operations
- **matplotlib & seaborn** – Data visualization
- **statsmodels** – Statistical modeling (OLS regression)
- **scipy** – Statistical tests

---

## 📁 Dataset

The dataset contains marketing spend across different channels and corresponding Sales figures.

**Expected Columns:**
- `TV`: Budget spent on TV advertising
- `Radio`: Budget spent on Radio advertising  
- `Social Media`: Budget spent on Social Media
- `Sales`: Revenue generated (target variable)

> **Note:** Update column names in the code if your dataset uses different headers.

---

## 🚀 How to Run the Project

### 1. Setup Environment

```bash
# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate

# Install dependencies
pip install pandas numpy matplotlib seaborn statsmodels scipy
```

### 2. Upload Dataset

- Place your dataset file (e.g., `marketing_data.csv`) in the project folder.
- Or upload it directly in Jupyter Notebook.

### 3. Run the Analysis

Open `marketing_regression_analysis.ipynb` (or the `.py` script) in Jupyter Notebook and run all cells step by step.

**Key Steps Covered:**
1. Load and explore data + handle missing values
2. Exploratory Data Analysis with visualizations
3. Identify the best predictor variable
4. Build OLS regression model
5. Model diagnostics (residual plots + tests)
6. Business interpretation & ROI recommendations

---

## 📈 Key Insights (Example)

After running the analysis, you will get:

- **Best Marketing Channel**: The variable with the highest correlation to Sales
- **R-squared**: How much variance in Sales is explained by the chosen channel
- **Coefficient**: Expected increase in Sales per $1 spent
- **Statistical Significance**: p-value of the relationship
- **ROI Estimate**: Rough return per dollar invested

---

## 📋 Project Structure

```
marketing-roi-analysis/
├── README.md
├── marketing_regression_analysis.ipynb     # Main Jupyter Notebook
├── marketing_data.csv                      # Your dataset
├── requirements.txt
└── outputs/                                # Saved plots and results (optional)
```

---

## 🔍 Model Diagnostics

The project includes diagnostic plots to check:
- **Linearity**: Residuals vs Fitted plot
- **Normality**: Q-Q Plot
- **Homoscedasticity**: Scale-Location plot + Breusch-Pagan test

---

## 💼 Business Recommendations

The final section provides actionable insights such as:
- Which channel to prioritize
- Expected ROI
- Budget allocation suggestions
- Next steps (e.g., multiple regression, A/B testing)

---

## 📌 Future Improvements

- Multiple Linear Regression
- Feature engineering (interaction terms, diminishing returns)
- Cross-validation and model comparison
- Predictive analytics for budget scenarios
- Export professional report (PDF/Word)

---

## 👤 Author

Built as a step-by-step learning project for Marketing Analytics using Python.

---

**Feel free to customize this README with your actual results, plots, and findings!**

```

**File Created Successfully!** 🎉

You can now view or download the `README.md` file. 

Would you like me to:
- Generate a full Jupyter Notebook (.ipynb) file with all the code?
- Create a `requirements.txt` file?
- Add sample output images or results section? 

Just let me know!