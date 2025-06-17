# HR Attrition Analysis Dashboard
```
An interactive Power BI dashboard backed by Python preprocessing to understand employee churn trends, identify high-risk segments, and help HR teams make data-driven retention decisions.
This project focuses on uncovering patterns that drive employee attrition, such as job role, monthly income, age, tenure, education, and performance. By combining Python for preprocessing and Power BI for visualization, this dashboard serves as a decision-making tool to help HR departments proactively manage workforce stability and retention.

🚀 Project Overview
This project combines the power of Python and Power BI to deliver meaningful insights from HR data.
Python (Pandas, Matplotlib, Seaborn) was used to:
Load and clean the raw employee dataset
Perform exploratory data analysis (EDA)
Visualize key distributions and relationships

Power BI was used to:
Build a clean, multi-page interactive dashboard
Highlight patterns in attrition using dynamic visuals
Make insights easy to understand for both technical and non-technical stakeholders

The dashboard helps answer key HR questions like:
Who is most likely to leave the company and why?
Which departments, education fields, and salary levels are most vulnerable to attrition?
How can HR teams intervene early to prevent avoidable turnover?

📂 Folder Structure
📁 visuals/ → Contains dashboard screenshots for preview and documentation
📁 data/ → Contains the cleaned HR dataset used in the project
📁 report/ → Final written report in both .docx and .pdf format
📄 DSBI.ipynb → Python notebook used for data preprocessing and EDA
📄 README.md → This file, which explains the project in detail
📄 HR_Dashboard.pbix → Power BI file for the HR Attrition dashboard


🧹 Preprocessing Steps (DSBI.ipynb)
The DSBI.ipynb notebook contains all the Python preprocessing steps. Here's a summary of what was done:
Data Loading: The original HR dataset was imported using Pandas
Cleaning: Duplicate rows and missing values were identified and removed
Exploration: Key attributes like Age, Job Role, Salary, and Attrition were analyzed using summary statistics and visual plots
Correlation: A heatmap was generated to understand the relationships between numerical variables
Export: The cleaned dataset was exported and used in Power BI for further visualization

🔍 Example Code Snippets
Some of the Python functions used include:
Checking missing values:
df.isnull().sum()

Identifying duplicate records:
df.duplicated().sum()

Plotting correlation heatmap:
sns.heatmap(df.corr(), annot=True)
These steps ensured a clean and reliable dataset was used to power the visual dashboard.

📌 Key Insights
Here are some of the most important insights derived from the dashboard:
Employees aged 26–35 with low monthly income are most likely to leave
Sales Executives and Laboratory Technicians face the highest attrition rates
Most employees who leave do so in their first year of employment, highlighting potential issues in onboarding or job fit
The use of electronic check as a payment method and month-to-month contracts are associated with higher churn
Employees without dependents or those in early-career roles are more prone to leaving
These insights can be used to build risk models and target specific groups with retention strategies.

✅ Recommendations
Based on the findings, here are several recommendations to help reduce employee attrition:
Improve onboarding experience: Provide better orientation, support, and mentorship for new hires
Engage high-risk roles: Focus on Sales Executives and Lab Technicians with growth opportunities and support systems
Offer incentives for long-term contracts: Encourage employees to commit beyond month-to-month employment
Revise salary structures: Consider revisiting compensation packages, especially for early-career and low-income employees
Use proactive monitoring: Implement early-warning systems to detect when at-risk employees may be considering leaving

🛠️ Tools Used
The following tools and technologies were used to complete this project:
Python (Pandas, Seaborn, Matplotlib): For data preprocessing and analysis
Power BI Desktop: For building the final visual dashboard
Excel: For minor formatting before importing data to Power BI
GitHub: For version control, documentation, and sharing the project

📎 How to Use
To explore this project, follow these steps:
Clone this repository to your local machine
Open and run the DSBI.ipynb file in Jupyter or Google Colab to view preprocessing
Open HR_Dashboard.pbix using Power BI Desktop to interact with the dashboard
Navigate through the dashboard pages (Summary, Job Role Insights, Risk & Recommendations)
Refer to the report/ folder for a detailed write-up of the analysis and outcomes

📬 Contact
Built with ❤️ by Meet Golani
📧 Email: golanimeet328@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/meet-golani/
If you found this project useful or have suggestions for improvement, feel free to reach out!
