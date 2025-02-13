# 📊 Data Science Job Salaries Analysis

## ✋ Introduction
In this project, I analyze the **Data Science Job Salaries** dataset, which I found on Kaggle (LINK). The dataset contains information about salaries and related factors such as **experience level, company location, company size**, and more.

For searching, exploring, and performing basic transformations, I used **SQL (PostgreSQL)**.

---
## 🔎 Objectives

### 1. Salary Insights
- What is the **average salary** for data professionals worldwide?
- How do **salaries vary by experience level**?
- Which **employment type** earns the most?

### 2. Geographical Trends
- What are the **top-paying countries**?
- Is there a **salary difference between an employee's residence and company location**?

### 3. Remote Work & Salary
- Do **remote jobs pay more or less** than onsite roles?
- Has the **number of remote job offers increased** over the past years?

### 4. Job Titles & Industry Insights
- What **job roles earn the most**?
- What is the **range of salaries for different job titles**?

---
## 💡 Findings and Insights

### 1. Salary Insights
- **What is the average salary for data professionals worldwide?**
  - The average salary for data professionals is **$112,298 USD**.

- **How do salaries vary by experience level?**
  - The following are the average salaries in USD:
    
    | Experience Level | Average Salary (USD) |
    |-----------------|---------------------|
    | Entry-level (EN) | 61,643 |
    | Mid-level (MI)  | 87,996 |
    | Senior-level (SE) | 138,617 |
    | Executive-level (EX) | 199,392 |

- **Which employment type earns the most?**
  - The highest-paying employment type is **Contract (CT)**, with a significant gap (~$70K) compared to **Full-time (FT)**.

---
### 2. Geographical Trends
- **What are the top-paying countries?**
  - The **top 5 highest-paying countries** (average salaries in USD):
    1. Malaysia - **$200,000**
    2. Puerto Rico - **$160,000**
    3. United States - **$149,194**
  - Note: The ranking is based on **average salaries by employee location**.

- **Is there a salary difference between an employee's residence and company location?**
  - Yes, the average salary difference is approximately **$40K**.
  - This is likely due to **onsite jobs**, such as Principal Data Engineer and Principal Data Scientist, which tend to offer **higher salaries**, thus inflating the average.

---
### 3. Remote Work & Salary
- **What are the top 5 jobs that most often require working locally?**
  - The **top 5 jobs** that require working **onsite**:
    1. **ETL Developer**
    2. **Head of Machine Learning**
    3. **Big Data Architect**
    4. **3D Computer Vision Researcher**
    5. **Lead Machine Learning Engineer**
  - Initially, I calculated the **total number of local job offers** per job title, but this approach favored **more common roles**. Instead, I calculated the **percentage of local job offers per job title**.

- **Has the number of remote jobs increased over the past three years?**
  - Yes, **remote job offers have increased nearly 7× from 2020 to 2022** (**36 → 228**).

---
### 4. Job Titles & Industry Insights
- **Which job has the largest salary range?**
  - **Principal Data Engineer** has the **largest salary range**, spanning **$415,000 USD**.

- **Which job had the highest number of beginners?**
  - The roles with the most **entry-level and mid-level professionals**:
    - **Data Scientist**
    - **Data Engineer**
    - **Data Analyst**

---
## 📌 Summary
This project explored **data science job salaries** using SQL for data exploration and transformation. The key takeaways include:
- **Salaries increase with experience**, with executives earning **~$200K USD**.
- **Contract jobs pay the highest**, but full-time positions dominate the dataset.
- **Malaysia, Puerto Rico, and the U.S. are the highest-paying countries**.
- **Remote jobs have significantly increased** since 2020.
- **Some onsite roles (e.g., Principal Data Engineer) drive salary differences**.
- **Beginner roles are most common in Data Science, Data Engineering, and Data Analysis**.
