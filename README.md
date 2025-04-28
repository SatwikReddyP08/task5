# Task 5: Titanic Exploratory Data Analysis

## Objective
Use Pandas, Seaborn & Matplotlib to explore the Titanic dataset and uncover patterns related to passenger survival.

## Data
- **Titanic.csv**: 891 training rows, 418 test rows
- Key columns: `Survived` (target), `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`

## EDA Steps
1. **Load & Inspect**: `.info()`, `.describe()`, `.isnull().sum()`
2. **Univariate Analysis**: Histograms for `Age`, `Fare`; countplots for `Survived`, `Sex`, `Pclass`, `Embarked`
3. **Bivariate Analysis**:  
   - Boxplot of `Fare` by `Survived`  
   - Countplot of `Survived` by `Sex` / `Pclass`
4. **Multivariate Analysis**:  
   - Correlation heatmap (`sns.heatmap`)  
   - Pairplot (`sns.pairplot`) for feature interactions
5. **Observations**: Written directly under each plot
6. **Summary**: Key findings at the end of notebook

## How to Run
1. Open **Task5_EDA.ipynb** in Jupyter.  
2. Execute all cells — plots and observations will render inline.  
3. Export to PDF via `File → Download as → PDF`.

## Key Insights
- Female passengers had significantly higher survival rates.  
- Lower class (`Pclass=3`) had lower survival odds.  
- Higher fares correlated with survival.  
- Age shows a skew; children and elderly survival patterns differ.

## Author
Satwik Reddy Pathapati
