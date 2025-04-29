# Titanic Dataset - Advanced Exploratory Data Analysis (EDA)

## Task Overview
This project is part of a Data Analyst Internship challenge. The goal is to perform an in-depth exploratory data analysis (EDA) on the Titanic dataset using unique and advanced visualizations to uncover key insights related to passenger survival.

##  Dataset Info
- **Filename**: Titanic-Dataset.csv
- **Source**: [Kaggle Titanic Challenge](https://www.kaggle.com/c/titanic)
- **Rows**: 891
- **Columns**: 12
- **Target**: Survived (0 = No, 1 = Yes)
  
## Libraries Used
- Python 3.x
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Google Colab

##  Visualizations Used
This version of the analysis uses different charts from traditional EDA to ensure a fresh and professional look.

###  Unique Charts in This Notebook:
- Violin Plot – Age distribution by survival
- Swarm Plot – Age vs Sex with survival hue
- Boxen Plot – Fare by passenger class
- Countplot with hue – Embarked vs survival
- Catplot – Survival by class and gender
- Jointplot – Age vs Fare by survival
- Correlation Heatmap (with triangle mask)
  
##  Key Findings
- Younger passengers, especially females, had higher survival rates.
- 1st class passengers paid higher fares and survived more often.
- Passengers who embarked from Cherbourg (C) had better odds of survival.
- Higher fare and lower Pclass were positively correlated with survival.
- Female survival rate in 1st class was significantly higher than in other groups.

##  Files Included
- `Titanic-Dataset.csv` — The dataset file
- titanic_EDA_Advanced.ipynb` — Colab notebook with full analysis
- `Titanic_EDA_Report_Advanced.pdf` — PDF report with visualizations and observations
- `README.md` — This file
- 
##  How to Run
1. Upload `Titanic-Dataset.csv` to your Google Colab environment.
2. Open `Titanic_EDA_Advanced.ipynb`.
3. Run all cells step by step.
4. Download the generated charts and insert them into the PDF report.
##  Conclusion
This EDA version offers a more visual and storytelling approach to the Titanic dataset. By using diverse and advanced Seaborn plots, the project highlights survival patterns with a refined and professional touch.
