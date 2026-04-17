# Student_Suicide_Trends-2018-2022
This repository contains a comprehensive Power BI analysis of student suicide cases in India over a five-year period. The goal of this project is to identify vulnerable demographics and geographic hotspots to provide data-driven insights for educational policymakers and mental health advocates.

🛠️ Tools & Technologies

Visualization: Power BI Desktop

Data Cleaning: Power Query (M Language)

Analytics: DAX (Data Analysis Expressions) for custom measures

Data Source: [Mention source, e.g., NCRB India / Open Government Data Portal]

🚀 The Data Process

1. Data Cleaning & Transformation (Power Query)
 
Standardization: Handled inconsistent naming conventions across state names (e.g., correcting "West Bengal" vs "W.B.").

Pivoting: Transformed year-wise columns into a long format for better time-series analysis.

Data Typing: Ensured "Number of Deaths" was formatted as an integer and "Year" as a date/period for accurate X-axis plotting.

2. Key DAX Measures Created
   
Total Deaths: SUM('Suicide Data'[Deaths])

YoY Growth %: To calculate the percentage increase in cases from 2018 to 2022.

Gender Distribution %: DIVIDE([Male Deaths], [Total Deaths], 0)

Dashboard:
<img width="1466" height="784" alt="Screenshot 2026-03-24 125842" src="https://github.com/user-attachments/assets/bb799cbe-64fc-4ea7-ad0d-e25bcf3920c9" />


📈 Visual Analysis Breakdown

Time Series Chart: Displays a sharp rise in cases, peaking at 15.4K in 2022, suggesting a post-pandemic impact on student mental health.

Treemap (Geographic): Highlights Maharashtra and Madhya Pradesh as the states with the highest volume of reported incidents.

Donut Chart (Gender): Reveals a significant disparity, with Males representing ~69.8% of the total cases.

Bar Chart (Education): Identifies that students at the Matriculate/Secondary level are at the highest statistical risk.

💡 Key Insights

Rising Trend: Student suicides have seen a steady climb since 2020, highlighting an urgent need for campus-based counseling.

Gender Gap: The high percentage of male student suicides suggests a need for gender-specific outreach programs.

Educational Pressure: The concentration of cases in secondary education levels points toward high-stakes exam pressure as a potential factor.
