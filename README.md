# School-Analytics-Dashboard-Data-Specialist-Showcase
Designed and implemented a comprehensive School Analytics Dashboard using Python, Google Colab, and AWS QuickSight to simulate real-world education data insights. This project demonstrates end-to-end data engineering, analytics, and visualization skills aligned with Talent Army’s Data Specialist role.

Pipeline: Google Colab → AWS QuickSight
Data Generation & Cleaning (Python / Google Colab)
Created synthetic student data (attendance, marks, engagement) with 500+ records.
Performed feature engineering to identify at-risk students based on attendance and performance.
Exported cleaned dataset as student_summary.csv.
Upload & Data Modeling (AWS QuickSight)
Uploaded CSV to QuickSight using SPICE for fast queries.
Defined data types, created calculated fields (e.g., AtRisk students), and set up hierarchies for drill-down analysis.
Built an interactive data model with global filters for Class, Subject, and At-Risk status.
Visualization & Dashboard
Table visual: Student-level Attendance %, Average Marks, and Engagement Score (with conditional formatting).
Bar chart: Attendance distribution by range.
Grouped bar chart: Average marks per class and subject.
Pie chart / stacked bar: Engagement Score by activity.
KPI card: Total at-risk students.
Enabled drill-down from Class → Student → Subject.
Key Skills Demonstrated
Data Engineering / ETL: Python Pandas, CSV generation, cleaning, feature engineering.
SQL & Analytics: SPICE dataset modeling, calculated fields, hierarchies, aggregations.
Dashboarding & Visualization: QuickSight table, KPI, bar chart, pie chart, stacked bar.
Machine Learning Insight: Random Forest-based at-risk student identification integrated into dashboard.
Cloud & Collaboration: AWS QuickSight for scalable analytics, reusable for multiple classes or schools.
