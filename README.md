# 🧠 AI/ML Job Market Data Analysis & Visualization

## Overview
This project analyzes trends, salaries, skills, and hiring patterns in the AI/ML job market. It provides insights on job demand, top locations, experience levels, salary distributions, in-demand skills, and trends over time. Additionally, it demonstrates simple machine learning modeling to predict salaries based on job title and experience level.

---

## Features

1. **Dataset Exploration**
   - View dataset shape, columns, and sample data.
   - Basic statistics and data quality checks.

2. **Data Cleaning**
   - Convert posted dates to datetime format.
   - Extract median salaries from salary ranges.

3. **Exploratory Data Analysis (EDA)**
   - Top job titles and locations.
   - Experience level distribution.
   - Salary distribution and salary vs experience level.

4. **Trend Analysis**
   - Monthly job posting trends.
   - Hiring trends for key roles (Data Scientist, Machine Learning Engineer, Data Engineer).

5. **Skill Analysis**
   - Identify most in-demand skills.
   - Analyze median salary by skill.
   - Word cloud of common job titles.

6. **Machine Learning**
   - Simple Linear Regression to predict salary based on job title and experience level.
   - R² score evaluation.

7. **Big Data Integration**
   - Load dataset into Spark DataFrame for scalable processing.

8. **Visualizations**
   - Static plots using Matplotlib & Seaborn.
   - Interactive plots using Plotly.

---

## Technologies Used
- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly, WordCloud
- Scikit-learn
- PySpark
- Google Colab (for cloud-based execution)

---

## Dataset
- The dataset `ai_job_market.csv` contains AI/ML job postings with the following columns (sample):
  - `job_title`: Title of the job posting
  - `location`: Job location
  - `experience_level`: Required experience level
  - `salary_range_usd`: Salary range in USD
  - `posted_date`: Date the job was posted
  - `skills_required` or `tools_preferred`: Required skills/tools

> **Note:** Update the file path in the notebook according to your Google Drive folder structure.

---

## How to Use
1. Clone or download the repository.
2. Open the notebook `AI_ML_Job_Market_Analysis.ipynb` in Google Colab.
3. Mount your Google Drive and update the dataset path.
4. Run the notebook cells sequentially to generate analysis, visualizations, and ML models.

---

## Insights You Can Get
- Top AI/ML job titles and their median salaries.
- Most in-demand skills and tools in the AI/ML market.
- Salary distributions across different experience levels.
- Hiring trends over time for key AI/ML roles.
- Predictive modeling of salary based on job title and experience.

---

## Author
- Yatharth Sharma

---

## License
This project is open-source and free to use for learning and educational purposes.

🔗 [LinkedIn](www.linkedin.com/in/vatsyatharth)| [Portfolio](https://github.com/UTSyatharth)
