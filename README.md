# Jobs_analysis_python
📌 Project Overview

This project analyzes the data job market in France, focusing on the most in-demand skills, highest-paying roles, and how skill type influences salary across popular data positions. Using job posting data, it highlights what employers want vs. what drives compensation, helping data professionals make informed career decisions.

❓ Research Questions

What are the top 3 most popular data roles and their most demanded skills?

Which skills are most in demand for Business Analysts?

How do salaries compare across top data roles in France?

What are the highest-paying vs most in-demand skills for Data Analysts?

How does skill category (cloud, programming, BI tools) relate to salary levels?

🛠️ Tools & Technologies Used

Jupyter Notebook – interactive data exploration

Python – core programming language

Pandas – data cleaning and analysis

Matplotlib & Seaborn – data visualization

AST (ast.literal_eval) – parsing structured text data

Hugging Face datasets – job market data sourcing

The Analysis


What are the most demanded skills for the top 3 most popular data roles?

I began by filtering the top 3 roles from which I got the top 5 skills. This querry highlights the most popular job titles and thier top skills. showinf which skills I should pay attention to depending on the roles I'm targetting

View my notebook with detailed steps here:
[Job_analysis_python.ipynb](https://colab.research.google.com/drive/1px8qMYH3MdCYcthDNyxbq582sdq_Ph3s?usp=sharing)

Results 


<img width="623" height="472" alt="image" src="https://github.com/user-attachments/assets/7b488399-3e06-4237-97bd-f971ad8994a1" />

Insights


Python and SQL are core for all top data roles

How are indemand skills trending for Business Analysts?


Overall, core data skills like SQL and Excel remain essential, while Python, Tableau, and Power BI are gaining importance, reflecting a growing emphasis on data analytics and visualization in Business Analyst roles


<img width="680" height="463" alt="image" src="https://github.com/user-attachments/assets/8bfb1cd0-f2df-4a1d-a64f-65d099f9bd6a" />

How well does jobs pay for top jobs in France?

<img width="757" height="463" alt="image" src="https://github.com/user-attachments/assets/65f8a960-fa05-4dac-b3a5-8339695f38bb" />

Engineering-heavy roles dominate top salaries in French IT.
Seniority matters more than title: “Senior” consistently adds 20–40%.
Roles closest to infrastructure, scalability, and production systems pay the most.

Highest paying jobs and most indemand jobs for data analysts in France?

Demand = SQL + BI + Python

High pay = infra + automation + cloud ownership

What most Data Analysts are hired for

What pushes salaries into the top decile

<img width="624" height="463" alt="image" src="https://github.com/user-attachments/assets/dd9ccf3c-8c39-46d3-bd4f-b6c6e16cd855" />

What is the relation between skill type and salary?

Cloud and programming skills sit in the high-salary/low-demand zone, while analyst tools dominate demand but deliver lower median pa

<img width="623" height="464" alt="image" src="https://github.com/user-attachments/assets/07555e65-7e0a-4e06-9124-9d4f81ad837d" />

📊 Key Insights

Python and SQL are foundational skills across all top data roles.

Engineering-heavy and cloud-related skills command the highest salaries.

Business Analyst roles increasingly require analytics and visualization tools (Python, Tableau, Power BI).

High demand does not guarantee high pay—scarcity and technical depth matter.

📚 What I Learned

How to extract meaningful insights from job market data

The importance of role convergence between analysts and engineers

How to visualize trade-offs between demand and salary

Practical handling of nested and semi-structured data in Python

⚠️ Challenges Faced

Cleaning inconsistent job titles and misclassified roles

Parsing stringified dictionaries using ast.literal_eval

Balancing readability and accuracy in dense visualizations

Avoiding misleading conclusions from outliers and hybrid roles

✅ Conclusion

The data job market in France rewards technical depth over ubiquity: while SQL and BI tools ensure employability, cloud, automation, and programming skills are key to breaking into top salary brackets. Aspiring data professionals should align skill development with both market demand and long-term salary potential.










