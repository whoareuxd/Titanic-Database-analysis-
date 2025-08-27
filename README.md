# Titanic Dataset Analysis

This repository contains a Jupyter Notebook that performs **exploratory data analysis (EDA)** on the Titanic dataset. The analysis focuses on **subtle, non-obvious patterns** rather than the usual survival statistics. The goal is to uncover unique insights about passengers’ demographics, fares, family size, and travel behavior.

## Dataset

The dataset used is `titanic.csv`, downloaded from [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data). Please place the CSV file in the same directory as the notebook before running it.

## Key Analyses and Insights

1. **Pairplot Analysis**
   - Explores numeric features (`Age`, `Fare`, `SibSp`, `Parch`, `Survived`)
   - Helps visualize correlations and clusters.

2. **Histograms**
   - Age distribution by survival status.
   - Shows children had higher survival, older passengers lower.

3. **Bar Charts**
   - Survival by gender, class, age group, and family size.
   - Reveals subtle patterns such as children with small families surviving more often.

4. **Heatmap**
   - Average Fare by family size (`SibSp` + `Parch`).
   - Highlights economic patterns among passengers.

5. **Line Charts**
   - Shows trends of average Fare and Age by passenger class or embarked port.
   - Reveals unusual groups, like young, high-paying 3rd-class passengers.

6. **Dot Chart (Scatterplot)**
   - Clean, simple visualization of `Fare` vs `Age` by class.
   - Captures non-obvious patterns: young, wealthy passengers in 3rd class traveling alone or in small groups.

All visualizations include professional Persian explanations for clarity.

## How to Use

1. Clone or download this repository.
2. Ensure `titanic.csv` is in the same folder as the notebook.
3. Open the notebook in Jupyter or VSCode.
4. Run each cell sequentially to generate the plots and insights.

## Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn
- Jupyter Notebook or VSCode with Python support

Install dependencies using:

```bash
pip install pandas matplotlib seaborn jupyter
# Titanic-Database-analysis-
