# ✋Introduction
In this project I will dive into the Data Science Job Salaries insights and find valuable and interesting informations. The Data Science Job Salaries (LINK) is a dataset that I found on kaggle. It contains information about salaries and informations correlated to them, like expirience level, company location, its size etc. 

# 🔎Objectives
1. Salary Insights
  * What is the **average salary** for data profesionals world wide?
  * How do **salaries vary by expirience** level?
  * Which **employment type** earns the most?
2. Geographical Trends
  * What are the top paying countries?
  * Is there a **salary difference** between an employee's **residence vs. company location**?
3. Remote Work & Salary
  * Do remote jobs pay more or less than onsite roles?
  * Did number of remote job offers increased over the past years?
4. Job Titles & Industry Insights
  * What job roles earn the most?
  * What is the range of salaries for different job titles?

# 🔬Technologies
For searching and diving into the dataset I will mostly use **SQL** (PostgresSQL). Advanced operations on dataset will be done in **python**. For visualization I will use **Power BI**. Other tools appearing in project: FEEEL IN THIS IF NEC!!!!!!!!!!!!!!!!!!!!!!!

# 💡Findings and Insights
1. Salary Insights
  * What is the **average salary** for data profesionals world wide? <br>
     The average salary for data provesionals is about **112298 $** (US dollars).
  * How do **salaries vary by expirience** level? <br>
     Following values are the average in USD. Shortcuts explanation: EN Entry-level / Junior MI Mid-level / Intermediate SE Senior-level / Expert EX Executive-level / Director
     | Subject | Value               |
     |---------|---------------------|
     | EN      | 61643               |
     | MI      | 87996               |
     | SE      | 138617              |
     | EX      | 199392              |
  * Which **employment type** earns the most? <br>
     The employment type that earns the most is CT- Contract Next with a huge difference (about 70K) is FT- Full time. [USD]
2. Geographical Trends
  * What are the top paying countries? <br>
     The **top 5** most paying countreis (in average) are: Malaysia 200000$, Puerto Rico 160000$, United States 149194$. For clarity by top paying countries it is ment how much average employee is being paid depending of his location.
  * Is there a **salary difference** between an employee's **residence vs. company location**? <br>
      Yes, there is a salary difference and it is to about 40K. I was curious where this difference come from so I dived deeper into this. The reason is most probably the fact that best paying jobs are onsite jobs ex. Principal Data Engineer, Drincipal Data Scientist. This jobs might inflate the average.
3. Remote/Local Work 
  * What are the top 5 jobs that most often require working locally? <br>
    Top 5 jobs that requiere working locally: ETL Developer, Head of Machine Learning, Big Data Architect, 3D Computer Vision Researcher, Lead Machine Learning Engineer. My first aproach was to calucalte number of local job offers for each job title, but this would favor most numerous jobs. Thus I calculated procent of job offers, for each job title that require working locally.
  * Did number of remote jobs increased over this 3 years? <br>
    Yes, definitely it did.The number of remote job offers **increased** almost **7 times** from 2020 to 2022 (36->228).
4. Job Titles & Industry Insights
  * What is the biggest range of salaries for different job titles? <br>
    The biggest range of salaries is for Principal Data Engineer: 415000$.
  * Which job had the biggest number of begginers? <br>
    The greatest number of beginners (in this dataset entry level, juniors/mids) occurred in the following fields: Data Scientist, Data Engineer, Data Analyst.
    
