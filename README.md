
---

# 🚢 Titanic Passenger Survival – Exploratory Data Analysis (EDA)

This project performs an in-depth **exploratory data analysis** on the RMS Titanic passenger dataset to identify the **key factors influencing survival**. The analysis explores how demographics, ticket class, fare, family size, and social titles contributed to survival outcomes using statistical visualizations and storytelling.

---

## 📊 Dataset Overview

* **Source:** Titanic dataset (publicly available via Kaggle)
* **Instances:** 891
* **Target Variable:** `Survived` (0 = No, 1 = Yes)
* **Features Include:**

  * **Demographics:** Name, Sex, Age
  * **Socioeconomic Info:** Pclass, Fare, Embarked, Title
  * **Family Information:** SibSp, Parch, FamilySize
  * **Travel Metadata:** Ticket, Cabin (dropped due to missing data)

> **Note:** Missing values in `Age` and `Embarked` were imputed; `Cabin` was dropped due to excessive null values.

---

## 📌 Project Objectives

* Clean and preprocess the Titanic dataset
* Perform **univariate, bivariate, and multivariate analysis**
* Discover **survival patterns by gender, class, family size, and age**
* Analyze **the impact of fare and embarkation port** on survival
* Create meaningful **visual narratives and high-impact insights**

---

## 🔧 Tools & Libraries

* **Python**
* **Pandas**, **NumPy**
* **Seaborn**, **Matplotlib**
* **ydata-profiling** for automated data summaries
* **Jupyter Notebook** for stepwise analysis

---

## 📈 Key Analyses Performed

* Count plots for survival by **gender**, **class**, **embarkation port**, and **alone/family**
* KDE plots for **age distribution** by survival status
* Box plots to compare **age and fare** across classes and survival
* Heatmaps for **correlation analysis**
* Grouped bar plots for **titles**, **family size**, and **age groups**
* Cross-tab heatmaps to detect **group-level survival trends**

---

## 📌 Insights

* **Females**, **children**, and **first-class passengers** had **significantly higher survival rates**.
* **Traveling alone** was associated with a **lower chance of survival**.
* **Higher fares and noble titles** were positively correlated with survival.
* Passengers **embarking from Cherbourg (C)** had better outcomes than those from **Southampton (S)**.
* **Larger families (5+)** and **senior passengers (60+)** had the **lowest survival rates**.

---

## 💡 Actionable Recommendations

* 🛟 Prioritize **balanced rescue access** across all socioeconomic classes in maritime protocols.
* 👨‍👩‍👧 Encourage **family-based evacuation strategies**, as survivors were more likely to travel in small groups.
* 🎫 Avoid reliance on **ticket fare tiers** in emergency planning—survival should not depend on fare class.
* 🧍‍♂️ Provide special attention to **solo travelers** and **elderly passengers** during crisis handling.
* 🧠 Leverage **title-based groupings** in predictive modeling for future passenger risk assessments.
* 🚨 Implement **embarkation-zone-based drills** to reduce location-driven evacuation disadvantages.

---

## 🧪 How to Run the Project

1. **Clone the repository:**

```bash
git clone https://github.com/amitkharche/EDA_Titanic_Dataset_amit_kharche.git
cd EDA_Titanic_Dataset_amit_kharche
```

2. **(Optional) Create and activate a virtual environment:**

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook:**

```bash
jupyter notebook
```

5. **Open the file:**

```
EDA_Titanic_Dataset_Analysis_amit_kharche.ipynb
```

and run all cells to reproduce the full analysis and visual insights.

---

## 📜 License

This project is intended for **educational and analytical purposes only**. Redistribution of the dataset should comply with its original license.

---

## 🤝 Acknowledgements

* Dataset adapted for EDA and learning
* Project inspired by survival analysis challenges in historical and maritime contexts

---

## ✨ Connect with Me

* [LinkedIn](https://www.linkedin.com/in/amitkharche)
* [Medium](https://medium.com/@amitkharche)
* [GitHub](https://github.com/amitkharche)

> If you found this project insightful, please ⭐ the repository and share your feedback!

---
