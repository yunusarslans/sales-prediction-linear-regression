# 📊 Sales Prediction Based on Advertising Budget

This project aims to predict sales based on advertising expenditures across three channels: TV, Radio, and Newspaper. It uses regression techniques and exploratory data analysis to understand how each medium impacts sales performance.

## 📁 Dataset

- Source: [Advertising.csv](https://www.statlearning.com/resources-first-edition)  
- Features:
  - **TV**: Advertising budget spent on TV (in thousands of dollars)
  - **Radio**: Advertising budget spent on Radio
  - **Newspaper**: Advertising budget spent on Newspaper
  - **Sales**: Number of units sold (target variable)

## 🔍 Project Workflow

1. **Data Loading & Inspection**
   - Overview using `.head()`, `.info()`, `.describe()`
   - Checked for missing values

2. **Exploratory Data Analysis (EDA)**
   - Correlation matrix with heatmap
   - Scatter plots: Advertising Budget vs. Sales
   - Interpretation of correlation strengths

3. **Model Training**
   - Linear Regression Model
   - Training/Test Split (80/20)
   - Model Evaluation with:
     - Mean Squared Error (MSE)
     - R² Score
     - Coefficient values

4. **Residual Analysis**
   - Residuals vs. Predicted plot
   - Model assumption checking

## 📈 Model Performance

- **R² Score**: ~0.90
- **MSE**: ~3.17
- TV ads show the strongest positive correlation with sales.
- Newspaper ads have the weakest predictive power.

## 📎 Dependencies

- Python 3.x
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install the dependencies with:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

## 💡 Future Work

- Try regularization (Ridge, Lasso)
- Apply polynomial regression
- Deploy the model using Flask/Streamlit

## 🧠 Author

- [Yunus Emre Arslan](https://github.com/YunusEmreArslan)
