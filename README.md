# 🎓 Student Performance Analytics Dashboard (Power BI)

This project analyzes student academic performance using demographic, social, and educational attributes from the UCI Student Performance dataset. Built with Power BI, the dashboard explores how various factors affect final grades and categorizes students based on performance levels.

## 📁 Dataset Source
UCI Machine Learning Repository – [Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance)

- Contains data on students from two Portuguese schools.
- Includes demographic, family, and academic information.
- `G1`, `G2`, and `G3` represent grades for three academic periods (0–20 scale).

---

## 📊 Dashboard Features

| Visual Type     | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| **Bar Charts**  | Average grades by school, sex, address, and family size                    |
| **Pie Chart**   | Performance distribution (Excellent, Average, Poor, Fail)                  |
| **Stacked Bars**| Parental education levels (`Medu`, `Fedu`) vs average grades               |
| **Scatter Plots**| Study time and absences correlation with final grade                      |
| **Cards/KPIs**  | Total students, overall average grade                                       |
| **Slicers**     | Filter by sex, address, internet access, study time, travel time, freetime |

---

## 🧠 Key Questions Answered

### ✅ Does higher parental education result in better grades?
**Yes.** Students whose parents (especially mothers) have higher education levels (3 or 4) tend to achieve higher average grades, as shown in the stacked bar chart comparing `Medu`/`Fedu` vs `avg_grade`.

### ✅ Does study time correlate with higher final scores?
**Generally yes.** The scatter plot shows a positive trend where students with higher study times (3 or 4) tend to score better on average.

### ✅ Is urban or rural location performing better?
**Urban students perform better.** The bar chart indicates that students from urban addresses (`U`) have significantly higher total and average grades compared to rural (`R`) counterparts.

### ✅ Any gender gap in scores?
**Slight differences observed.** The bar and scatter visuals show that female students slightly outperform male students, particularly in higher average score categories.

---

## 📌 Technologies Used
- **Power BI Desktop**
- **DAX for calculated columns**
- **UCI Student Performance Dataset**
- **CSV Data Source**

---

## 📎 Files Included
- `Student_Performance.pbix` – Power BI dashboard file  
- `student-mat.csv` – Dataset (Math course only)  
- `screenshots/` – Dashboard image  
- `README.md` – Project overview and analysis

---

## 📣 Author

**Kiranpreet Kaur**  
[LinkedIn Profile](https://www.linkedin.com/in/kiranpreet-kaur-a5a67a268)

---

## 🔖 License

Dataset: [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)  
Project code: Open for educational use.

