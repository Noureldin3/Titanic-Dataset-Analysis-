# 🚢 Titanic Dataset Analysis

## 📌 Overview

-   Analysis of Titanic dataset to uncover survival patterns.\
-   Includes **Jupyter Notebook**, **Power BI dashboard**, and **summary
    report**.

## 📂 Files

-   `final_notebook.ipynb` → Data cleaning, feature engineering, EDA.\
-   `final_dashboard.pbix` → Interactive Power BI dashboard.\
-   `Titanic Dataset Analysis summary f.pdf` → Key insights &
    conclusions.

## ⚙️ Key Steps

-   Handled missing values (`Age`, `Embarked`, dropped `Cabin`).\
-   Extracted `Title` from names.\
-   Encoded categorical variables.\
-   Selected key predictors: `Class`, `Sex`, `Age`, `Fare`, `Title`.

## 📊 Insights

-   **Females**: 74% survival vs **Males**: 19%.\
-   **1st Class**: 63% survival vs **3rd Class**: 24%.\
-   Titles (`Miss`, `Mrs.`) had higher survival odds than `Mr.`.\
-   Young females (\<40) had the highest survival rates.

## 📝 Conclusion

-   Survival depended on **gender, class, and title**.\
-   **Title** was a surprisingly strong predictor (e.g., *Master* had
    higher survival than adult men).

## 🔧 Tools

-   Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)\
-   Power BI\
-   Jupyter Notebook
