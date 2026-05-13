AI Adoption & Business Impact Analysis

This project analyzes global AI adoption trends across industries, regions, and companies using exploratory data analysis (EDA) techniques. The notebook analyzes the data and presents how AI investment, adoption maturity, automation, and reskilling efforts impact productivity, revenue growth, and employment.

The project includes:
- Data cleaning and preprocessing
- Handling missing and duplicate values
- Statistical analysis
- Correlation analysis
- Multivariate analysis
- charts and heatmaps
- Business insights extraction

Dataset

| Feature | Description |
|---|---|
| response_id | Unique survey response identifier |
| company_id | Unique company identifier |
| survey_year | Year of survey collection |
| quarter | Survey quarter |
| country | Company country |
| region | Geographical region |
| industry | Industry sector |
| company_size | Company size category |
| num_employees | Total number of employees |
| annual_revenue_usd_millions | Annual revenue in USD millions |
| company_founding_year | Company establishment year |
| company_age | Age of the company |
| company_age_group | Categorized company age group |
| ai_adoption_rate | Percentage of AI adoption |
| ai_adoption_stage | AI maturity/adoption stage |
| years_using_ai | Number of years using AI |
| ai_primary_tool | Primary AI tool used |
| num_ai_tools_used | Number of AI tools used |
| ai_use_case | Main AI application/use case |
| ai_projects_active | Number of active AI projects |
| ai_training_hours | Employee AI training hours |
| ai_budget_percentage | Budget allocated to AI |
| ai_maturity_score | AI maturity evaluation score |
| ai_failure_rate | Rate of AI project failures |
| ai_investment_per_employee | AI investment per employee |
| regulatory_compliance_score | Compliance assessment score |
| data_privacy_level | Data privacy protection level |
| ai_ethics_committee | Presence of AI ethics committee |
| ai_risk_management_score | AI risk management evaluation |
| remote_work_percentage | Percentage of remote employees |
| employee_satisfaction_score | Employee satisfaction rating |
| task_automation_rate | Percentage of automated tasks |
| time_saved_per_week | Weekly time saved using AI |
| productivity_change_percent | Productivity improvement percentage |
| jobs_displaced | Number of jobs displaced |
| jobs_created | Number of new jobs created |
| reskilled_employees | Employees reskilled for AI |
| revenue_growth_percent | Revenue growth percentage |
| cost_reduction_percent | Operational cost reduction percentage |
| innovation_score | Innovation performance score |
| customer_satisfaction | Customer satisfaction rating |
| survey_source | Source of survey data |
| data_collection_method | Method used to collect data |

Programming Language
- Python 3

Libraries
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

Key Analysis Performed
1. Data Inspection
- Visual inspection of records
- Dataset shape analysis
- Statistical summaries

2. Data Cleaning
- Missing value detection
- Removing null records
- Duplicate record identification and removal
- Data type verification

3. Exploratory Data Analysis (EDA)
- Country-wise company distribution
- Industry-wise AI adoption
- Region-wise analysis
- Revenue analysis across countries
- AI maturity analysis
- Productivity trend analysis

4. Correlation & Relationship Analysis
- Heatmap generation
- Pairplot visualizations
- Multivariate analysis
- AI investment vs productivity analysis
- AI maturity vs revenue growth analysis

5. Workforce Impact Analysis
- Automation vs job displacement
- AI-driven job creation
- Reskilling investments
- Industry impact comparisons

Major Insights
Global AI Adoption
- France shows a high number of companies working on AI.
- Asia appears to lead among regions in AI adoption.
- Technology and Finance sectors dominate AI usage.

Revenue & Productivity
- Companies investing more in AI generally achieve higher productivity gains.
- AI maturity correlates positively with revenue growth.
- Large companies convert AI investments into business outcomes more effectively.

Workforce Trends
- AI is creating jobs in several industries.
- High automation may also lead to workforce displacement.
- Companies investing in automation often increase reskilling initiatives.

Visualizations Included

The notebook contains:
- Heatmaps
- Pairplots
- Line charts
- Bar charts
- Correlation matrices
- Comparative trend analysis


How to Run the Project

1. Clone the Repository

bash
git clone https://github.com/HemDesh/Data_Analysis_on_AI_Adoption_and_Workforce_Impact


2. Install Dependencies

bash
pip install pandas matplotlib seaborn notebook

3. Launch Jupyter Notebook
notebooks/main.ipynb

