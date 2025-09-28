# Titanic Dataset - Data Cleaning & Exploratory Data Analysis (EDA)

This project performs **data cleaning** and **exploratory data analysis (EDA)** on the Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic) (also provided in the [Prodigy InfoTech dataset repo](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%202)).

---

## 📂 Project Structure
- `titanic_eda.py` → Python script for data cleaning and EDA  
- `titanic_eda.ipynb` → Jupyter Notebook version (code + visualizations)  
- `requirements.txt` → List of Python dependencies  
- `README.md` → Project documentation  

---

## ⚙️ Steps Performed
### 1. Data Cleaning
- Handled missing values:
  - Filled missing **Age** with median  
  - Filled missing **Embarked** with mode  
  - Dropped **Cabin** (too many missing values)  
- Removed unnecessary columns (`PassengerId`)  

### 2. Exploratory Data Analysis (EDA)
- **Univariate Analysis**: Distribution of age, fare, survival counts  
- **Bivariate Analysis**: Survival vs. gender, class, embarkation  
- **Correlation Analysis**: Heatmap to identify relationships between variables  

---

## 📊 Key Insights
1. **Gender**: Females had a much higher survival rate than males.  
2. **Class**: First-class passengers were more likely to survive compared to lower classes.  
3. **Age**: Younger passengers had slightly better survival chances.  
4. **Embarkation**: Passengers from port **C** had higher survival probability.  
5. **Fare**: Higher fare was positively correlated with survival (wealthier passengers survived more).  

---

## Tech Stack

**Python**
**Pandas**
**NumPy**
**Matplotlib**
**Seaborn**

## 📌 Credits

Dataset: Kaggle Titanic Dataset
Assignment Task: Prodigy InfoTech - Data Science Internship
