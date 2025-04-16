📊 Exploratory Data Analysis (EDA) – Student Performance Dataset

This project presents a detailed exploratory analysis of the    StudentsPerformance.csv    dataset.  
The goal is to uncover insights about how different factors such as gender, parental education, and test preparation affect students' academic performance across Math, Reading, and Writing.

---

   📁 Dataset Information

-    
-    File   : `StudentsPerformance.csv`  
-    Records   : 1000 students  
-    Features   :
  - `gender`
  - `race/ethnicity`
  - `parental level of education`
  - `lunch` (standard/reduced)
  - `test preparation course` (completed/not completed)
  - `math score`
  - `reading score`
  - `writing score`

---

   🛠️ Tools & Libraries Used

- Python 3 (Google Colab)
- Pandas
- Matplotlib
- Seaborn
- FPDF / Word (for PDF reporting)

---

   🧪 EDA Steps Followed

  # ✅ Step 1: Data Loading & Cleaning
- Loaded the dataset into a DataFrame
- Cleaned column names (lowercase, replaced spaces with underscores)
- Checked for missing values & duplicates

  # ✅ Step 2: Dataset Overview
- Displayed top records and summary stats
- Used `.info()` and `.describe()` for data profiling

  # ✅ Step 3: Univariate Analysis
- Countplots for `gender`, `lunch`, `test preparation`, etc.
- Histograms for `math`, `reading`, and `writing` scores
- Boxplots to detect outliers

  # ✅ Step 4: Correlation & Pairplot
- Correlation matrix heatmap
- Pairplot to visualize score relationships

  # ✅ Step 5: Bivariate Analysis
- Average scores grouped by:
  - `gender`
  - `race/ethnicity`
  - `test preparation course`

---

   📌 Key Insights

- 🧠    Reading & Writing    are highly correlated
- 👩‍🎓    Female students    score higher in Reading and Writing
- 👨‍🎓    Male students    slightly outperform in Math
- 📚    Test prep course    significantly boosts scores
- 🍽️    Standard lunch    group scores better than reduced/free lunch
- 🏅    Group E    students have the highest average performance

---
   📌 Conclusion

This analysis shows how demographic factors and preparation influence academic success.  
These insights can help in designing personalized education strategies and support programs.

---

   📬 Author

> ✍️ *Somya Sinha*  
> 📅 *Task 5*  
> 🧠 *Feel free to have any discussions and share any valuable insights-www.linkedin.com/in/somyasinha100 *
