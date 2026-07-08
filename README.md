Green Destination – HR Employee Attrition Analysis
An end-to-end HR analytics project analyzing employee attrition at Green Destinations, built with Tableau, and Excel/SQL for data preparation. The project identifies attrition drivers across department, education, job satisfaction, age, and gender, and translates the findings into HR decisions.

Live Dashboard: Tableau Public – Green Destination HR Department

Objective
Green Destinations was experiencing increased employee attrition. The HR Director requested analysis to:

Determine the attrition rate (% of employees who have left).
Identify whether factors such as age, years at the company, and income influence attrition.
Goal: Provide insights and analysis to help HR reduce future attrition through targeted, data-backed interventions.

Tech Stack
Tool	Purpose
Tableau	Interactive dashboard creation and visualization
Excel / SQL	Data wrangling, cleaning, and sourcing
Dataset
1,470 employee records (IBM HR Analytics Employee Attrition dataset)
Fields include: Age, Attrition, Department, Education Field, Gender, Job Satisfaction, Job Role, Marital Status, Monthly Income, OverTime, Years at Company, and more.
Key Performance Indicators (KPIs)
Employee Count & Active Employees
Attrition Count & Attrition Rate
Attrition by Gender
Department-wise Attrition
Education Field–wise Attrition
Job Satisfaction vs. Attrition
Attrition by Age Group
Headline numbers: 1,470 total employees · 237 attritions · 16.12% attrition rate · 1,233 active employees · avg. age 37

Key Findings
1. Department-wise Attrition
Research & Development has the highest attrition count (133 employees / 56.1% of all departures).
Human Resources has the lowest attrition count (12 employees / 5.1% of departures).
Note: Sales has the highest attrition rate relative to headcount, even though R&D has the highest raw count — worth calling out separately when rate vs. volume matters.
2. Education Field–wise Attrition
Life Sciences employees show the highest attrition (89 departures).
Medical (63) and Marketing (35) also show significant attrition — marketing roles' pressure/targets may explain higher turnover.
Technical Degree shows moderate attrition (32).
Other and Human Resources fields show the lowest attrition (11 and 7), possibly due to smaller team size or higher satisfaction.
3. Job Satisfaction
High satisfaction (Level 4): Sales Executives (112) and R&D staff (95) report the most top-tier satisfaction.
Low satisfaction (Levels 1–2): Sales Executives and R&D also show high counts at the bottom end (Sales: 69 @ Level 1, 54 @ Level 2; R&D: 54 @ Level 1, 53 @ Level 2) — these two groups are the most polarized on satisfaction.
4. Attrition by Age Group
Peak workforce age is 34 (155 employees) — the core of the workforce is early-to-mid 30s.
Growth phase (18–34): headcount rises steadily, suggesting active hiring/retention of younger employees.
Decline phase (35+): steady drop from 155 (age 34) to 5 (age 60), consistent with retirement and natural attrition.
Employees aged 28–38 make up the bulk of the workforce and likely carry key operational responsibilities.
5. Attrition by Gender
150 male employees left vs. 87 female employees — male attrition is notably higher in absolute terms.
Recommendations
Insight	Recommended Action
More males are leaving than females	Conduct exit interviews/surveys focused on gender-specific engagement gaps
Workforce is concentrated in ages 28–36	Prioritize retention and career development programs for this segment
Life Sciences & Medical backgrounds show high attrition	Review job satisfaction, pay parity, and growth paths in these fields
Sales shows high attrition alongside lower satisfaction	Reassess sales targets, commission structure, support systems, and wellness programs
Job satisfaction and attrition are closely linked	Improve role clarity, recognition, and growth opportunities in low-satisfaction teams
Younger females and mid-career males are highest flight risk	Offer mentorship/flexible work for early-career women; address burnout/stagnation for mid-career men
R&D and HR show comparatively low attrition	Document and replicate their retention practices across other departments
Next steps for a v2 of this project:

Add a simple predictive model (e.g., logistic regression / decision tree) to rank attrition drivers by statistical importance rather than description alone.
Break out attrition rate (not just count) by department in the main dashboard view, since rate and volume tell different stories.
Layer in OverTime as an explicit KPI — it shows one of the strongest attrition splits in the dataset.
Project Structure
├── data/                  # Source data (Excel/SQL exports)
├── dashboard/             # Tableau workbook (.twbx)
├── Green_Destination_Presentation.pdf   # Project summary deck
└── README.md
Author
Arif Bin Mushtaq Ramanujan College, University of Delhi 📧 loneasuu123@gmail.com , arifbinmushtaqq@stats.du.ac.in
