# Academic-Performance-Student-Analysis
​📌 Project Overview
​This project provides an end-to-end data analytics solution built using Microsoft Power BI to evaluate institutional academic performance, student engagement, department-wise enrollments, demographics, and financial collections.
​The dashboard synthesizes data across multiple entities (students, courses, departments, financials, and library logs) into actionable insights using Descriptive, Diagnostic, Predictive, and Prescriptive analytics frameworks.

​📊 Key Business Metrics (KPIs)
​Total Students: 1,000 (1\text{K})
​Total Enrollments: 13,000 (13\text{K})
​Total Courses Offered: 55
​Overall Pass Rate: 71.64\% (11\text{K} Passed Count)
​Average Attendance Rate: 90.01\% (378\text{K} Attendance Records)
​Average Assignment Score: 82.42
​Total Revenue / Fee Collected: \$253.04\text{M}
​Average Payment Amount: \$100.45\text{K}
​Library Engagement: 5\text{K} Total Books Loaned
​Gender Ratio: 51\% Male (507) | 49\% Female (493)

​🎯 Four Types of Data Insights
​1. 🔍 Descriptive Analytics (What Happened?)
​Demographics & Geography: Balanced gender distribution across major metropolitan hubs in India (Bengaluru, Chennai, Mumbai, Hyderabad, Delhi, etc.).
​Enrollment Trends: Computer Science leads department enrollments at 13.85\% (2\text{K} enrollments), followed by Mechanical, Electronics, Physics, and Finance.
​Financial Performance: Total revenue generated stands at \$253.04\text{M}, collected via multiple payment streams including Bank Transfer, Demand Draft, and Online Gateways.

​2. 🩺 Diagnostic Analytics (Why Did It Happen?)
​Attendance vs. Performance: A positive correlation exists between attendance rate (90.01\%) and assignment scores (82.42).
​Resource Utilization: High library book utilization (5\text{K} loans) directly links to higher pass rates in core courses like Introduction to AI, Calculus I, and University Physics.
​Departmental Variance: Fluctuations in pass rates between Fall and Spring semesters are driven by variations in assignment completion rates and course difficulty across departments.

​3. 🔮 Predictive Analytics (What is Likely to Happen?)
​Assignment Progress Trends: Score progression curves show periodic dips preceding term deadlines, indicating potential performance drops if submission schedules are delayed.
​At-Risk Students: Based on the current 71.64\% pass baseline, approximately 28.36\% of students are at risk of underperforming if attendance drops below the 90\% threshold.

​4. 💡 Prescriptive Analytics (What Actions Should Be Taken?)
​Academic Interventions: Implement targeted tutoring in departments with lower pass rates to elevate the institutional baseline above 71.64\%.
​Automated Reminders: Deploy automated Power BI threshold alerts for assignment deadlines to reduce submission delays.
​Resource Promotion: Expand library resource promotion for underperforming subjects to leverage the proven correlation between reading materials and improved grades.

​🛠 Tech Stack & Tools Used
​Business Intelligence: Microsoft Power BI Desktop
​Data Modeling: Star Schema (Fact & Dimension Tables)
​Calculations: DAX (Data Analysis Expressions) for KPIs and aggregated measures
​Data Visualizations: Custom Line Charts, Donut Charts, Waterfall/Driver Charts, Matrix Tables, Geographical Maps, and KPI Cards
​📂 Project Structure
├── README.md                              <- Project Documentation
├── Data/
│   ├── Fact_Academic_Performance.csv      <- Academic & Grades Data
│   ├── Fact_Financials.csv                <- Fee & Payment Data
│   └── Dim_Students.csv                   <- Student Demographics & Profiles
├── PowerBI/
│   └── Student_Analytics_Dashboard.pbix   <- Main Power BI File
└── Screenshots/                           <- Report Dashboard Layouts
