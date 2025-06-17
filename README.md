#📊 HR Attrition Analysis Dashboard
An interactive Power BI dashboard backed by Python preprocessing to understand employee churn trends, identify high-risk segments, and help HR teams make data-driven retention decisions.

🚀 Project Overview
This project combines:
Python (Pandas, Matplotlib, Seaborn) for data cleaning, preprocessing, and EDA
Power BI to build a clean, interactive dashboard that highlights attrition patterns by age, salary, job role, education, performance, and tenure.

It answers key HR questions like:
Who is most likely to leave?
Which departments or roles are at highest risk?
How do salary, education, and tenure impact attrition?

📂 Folder Structure
📁 visuals/      → Dashboard screenshots  
📁 data/         → HR_Analytics.csv (sample dataset)  
📁 report/       → Final report (.docx / .pdf)  
📄 DSBI.ipynb    → Jupyter Notebook for preprocessing  
📄 README.md     → This file  
📄 HR_Dashboard.pbix → Power BI file

🧹 Preprocessing Steps (DSBI.ipynb)
Data Loading: Imported HR_Analytics.csv
Cleaning: Removed duplicates and handled missing values
Exploration: Visualized correlations between features
Export: Cleaned dataset exported for Power BI dashboard

🔍 Example:
df.isnull().sum()
df.duplicated().sum()
sns.heatmap(df.corr(), annot=True)

📌 Key Insights
Employees aged 26–35 with low salaries are most at risk
Sales Executives and Laboratory Technicians show the highest churn
First-year attrition is extremely high — better onboarding is critical
Electronic check payment method and month-to-month contracts correlate with exits

✅ Recommendations
Improve onboarding experience
Increase engagement in high-churn roles
Offer incentives for long-term contracts
Reevaluate salary structure for junior roles

🛠️ Tools Used
Python (Pandas, Seaborn, Matplotlib)
Power BI Desktop
Excel (for minor formatting)
GitHub (for version control & publishing)

📎 How to Use
Clone this repo
Run DSBI.ipynb to explore the data and preprocessing steps
Open HR_Dashboard.pbix in Power BI to interact with the dashboard
View the report/ folder for a summarized project report

📬 Contact
Built with ❤️ by Meet Golani
📧 golanimeet328@gmail.com
🔗 https://www.linkedin.com/in/meet-golani/
