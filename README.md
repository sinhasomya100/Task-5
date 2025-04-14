🚢 Titanic Dataset – Exploratory Data Analysis (Task 5)

This repository contains my complete solution to **Task 5** of the Data Analyst Internship — performing **Exploratory Data Analysis (EDA)** on the Titanic dataset using Python and Jupyter Notebook.

---

 🎯 Task Objective

Explore the Titanic dataset, handle missing values, visualize the data using meaningful plots, and generate valuable insights as a beginner Data Analyst.

---

 📂 Files Included

| File                          | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| `Titanic_EDA_Task5.ipynb`     | Main Jupyter Notebook with code, analysis, and visuals                     |
| `Titanic_EDA_Task5.pdf`       | Exported notebook in PDF format                                            |
| `Titanic_EDA_FULL_Report.pdf` | Beginner-friendly **Report of Findings** with summary, insights & conclusion |
| `TASK 5 DA.pdf`               | Official internship task PDF for reference                                |

---

🛠️ Tools & Technologies

- **Language:** Python  
- **Platform:** Jupyter Notebook  
- **Libraries:**  
  - 📊 Pandas  
  - 📈 Matplotlib  
  - 🧼 Seaborn  

---

🔍 What I Did

 ✅ 1. Data Cleaning
- Handled null values:
  - `Age` → filled with **median**
  - `Embarked` → filled with **mode**
  - `Cabin` → dropped (too sparse)
- Checked data types & missing values with `.info()` and `.isnull().sum()`

 ✅ 2. Univariate Analysis
- Countplots for categorical columns: `Survived`, `Sex`, `Pclass`, `Embarked`
- Histograms for numerical columns: `Age`, `Fare`
- Boxplots to detect outliers and distributions

 ✅ 3. Bivariate Analysis
- `Survived` vs `Sex`, `Pclass`, `Fare`, `Age`, and `Embarked`
- Found strong relationship between survival and features like `Sex`, `Class`, `Fare`
- Correlation matrix heatmap created

 ✅ 4. Insights + Visual Observations
- Observations written below each visual
- Used Seaborn & Matplotlib for better clarity
- Summary section added at end of notebook

 ✅ 5. Interview Questions Section
- Commonly asked EDA questions answered at the bottom of the notebook to help beginners

---

 📊 Visualizations Created

- 📌 Countplot  
- 📌 Histogram  
- 📌 Boxplot  
- 📌 Correlation Heatmap  
- (Optional) Pairplot skipped for performance

---

💡 Summary of Findings

- 👩‍🦰 **Females** had much higher survival rate than males  
- 🏰 **1st class** passengers had better survival chances  
- 👶 **Children** (under 10) showed better survival  
- 💰 Higher **Fare** → higher chances of survival  
- 🧳 Most passengers embarked from **Southampton (S)**  
- ❌ `Cabin` was removed due to 77% missing values

-🙌 Final Note

Thank you for reviewing this project!  
It helped me apply everything I’ve learned about real-world data cleaning, plotting, insight extraction, and storytelling through data.

> 💬 Feel free to explore the notebook or check the full report to see the insights!
www.linkedin.com/in/somyasinha100



