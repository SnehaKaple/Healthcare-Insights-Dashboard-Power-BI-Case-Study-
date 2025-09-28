# Healthcare-Insights-Dashboard-Power-BI-Case-Study-
This project focuses on leveraging data analytics and business intelligence (BI) to provide deep insights into a healthcare facility.


## Project Overview
This project focuses on leveraging data analytics and business intelligence (BI) to provide deep insights into a healthcare facility's operational efficiency and patient care quality. It analyzes raw patient encounter data to uncover critical trends related to patient flow, wait times, departmental performance, and satisfaction levels.
The resulting dashboard serves as a crucial tool for hospital administrators and department heads to make immediate, data-driven decisions that enhance patient experience and optimize resource allocation.


## Objectives
- Build an interactive, single-page dashboard to monitor core healthcare KPIs in real-time.
- Track Average Wait Time (Min) and Patient Satisfaction Score across different time periods.
- Analyze Patient Volume (Total Encounters) by department and hour of the day to identify staffing needs and peak flow bottlenecks.
- Measure service level by calculating the Percentage of Patients Seen Within 30 Minutes.
- Implement a resilient data ingestion process that scales automatically with new monthly patient logs.

## Tools & Techniques
- **Microsoft Power BI**
- Power Query (M Language): Used for resilient folder-based data ingestion, data cleaning, date/time splitting, and ID normalization.
- DAX (Data Analysis Expressions): Used to create powerful time-intelligence measures (MoM Growth %) and complex service-level metrics.
- Star Schema Modeling: Implementation of key relationships between the Fact_Encounters and dimensional tables.

  ##  Dashboard Preview
Below are snapshots of the PowerBI dashboard (for quick viewing).  

### Overall Dashboard  
![Dashboard Overview](https://github.com/SnehaKaple/Healthcare-Insights-Dashboard-Power-BI-Case-Study-/blob/main/Healthcare%20Dashboard.png)

### Healthcare Report(Problem_statement).
![Problem Statement](https://github.com/SnehaKaple/Healthcare-Insights-Dashboard-Power-BI-Case-Study-/blob/main/Problem%20Statement%20Analysis.pdf)

### Healthcare (Datasets) 
![Datasets](https://github.com/SnehaKaple/Healthcare-Insights-Dashboard-Power-BI-Case-Study-/blob/main/Hospital%20ER_Data.csv)

### Healthcare Final Project
![Project](https://github.com/SnehaKaple/Healthcare-Insights-Dashboard-Power-BI-Case-Study-/blob/main/Healthcare-Project.pbix)



## Key Insights
- Wait Time Improvement: The analysis confirms a strong correlation between high hourly patient volume and spikes in average wait times, pinpointing specific hours for optimized staffing.
- Satisfaction Drivers: Patient Satisfaction Scores vary significantly between departments, suggesting targeted quality improvement initiatives are needed in specific areas (e.g., Emergency vs. Radiology).
- Service Level Success: The Seen Within 30 Min % metric acts as a crucial benchmark, revealing whether the facility is meeting its patient experience goals.
- Data Resilience: The ingestion setup ensures the dashboard is future-proof, automatically incorporating new monthly data files without manual query maintenance.


##  Author
**Sneha Kaple**  
B.Tech in Artificial Intelligence | Data Analytics Enthusiast  
[LinkedIn](https://www.linkedin.com/in/sneha-kaple-analytics/) | [GitHub](https://github.com/SnehaKaple)


