# 📊 AI Job Market Analysis
---

## 📌 Project Overview
This project analyzes an **AI Job Market Dataset** to understand:
- In-demand skills  
- Industry-wise Avg salary   
- Salary distribution  
- Key insights for job seekers  

The analysis is performed using **Python (Pandas, Matplotlib, Seaborn)** in Jupyter Notebook.

---

## 🎯 Objectives
- Identify **top skills in demand**
- Analyze **industry-wise Salary requirements**
- Compare **average salary across industries**
- Visualize insights using charts and heatmaps

---

## 🗂️ Dataset Features

- `job_id` – Unique job identifier  
- `company_name` – Company offering the job  
- `industry` – Industry category  
- `job_title` – Job role  
- `skills_required` – Required skills  
- `experience_level` – Entry / Mid / Senior  
- `employment_type` – Full-time / Part-time / Contract  
- `location` – Job location  
- `salary_range_usd` – Salary range  
- `posted_date` – Job posting date  
- `company_size` – Size of the company  
- `tools_preferred` – Tools required  

---

## 🛠️ Data Preprocessing
- Converted `posted_date` → datetime  
- Split `salary_range_usd` into:
  - `min_salary`
  - `max_salary`
  - `avg_salary`
- Cleaned `skills_required` column  
- Handled missing values using `dropna()` and `errors='coerce'`

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 1. Top Skills in Demand
- Extracted and counted most frequent skills  
- Visualized using bar chart  

### 🔹 2. min & max salary Analysis
- Split and exploded skills column  
- Grouped by min salary and max salary  
- Visualized using bar charts and heatmaps  

### 🔹 3. Industry vs Avg Salary Analysis
- Calculated average salary per industry  
- Compared using bar chart  

---

## 📈 Visualizations Used
- 📊 Bar Charts  
- 🔥 Heatmaps  
- 🥧 Pie Charts  

---

## 🧠 Key Insights
- Skills like **Python, SQL, Machine Learning** are highly demanded  
- Different industries require different skill sets  
- Salary varies significantly across industries  
- Roles like Data Analyst, Data Scientist and ML engineer appear most frequently.

---

## 💻 Technologies Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone <your-repo-link>

2.  Install dependencies:
 pip install pandas matplotlib seaborn

3. Open Jupyter Notebook and run the file
```
---
## 📌 Conclusion

   This project helps understand the AI job market trends, including skills demand and salary insights.
   
---
## 🔗 Future Improvements
- Build Power BI / Tableau dashboard
- Add machine learning model for salary prediction
- Perform time-based trend analysis
---
## 🙌 Author

Preethi

---

If you want 🔥 I can next:
- Add **project screenshots section**
- Give **GitHub description (2 lines)**
- Write **LinkedIn post (to get recruiters attention)** 👍

