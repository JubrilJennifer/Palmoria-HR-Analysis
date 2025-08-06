# Palmoria-HR-Analysis
EDA project for Capstone submission
# Palmoria Group HR Analysis 

##  Project Overview
This analysis explores employee data for Palmoria Group to uncover gender representation, salary gaps, bonus fairness, and HR risks. The project uses Power BI for visualization and insights.

The company faced public criticism over gender inequality, prompting this internal data review.

##  Data Cleaning
- Replaced missing Gender values with "Unspecified"
- Removed employees with no salary or with NULL departments
- Standardized rating labels
- Joined bonus rules using Department and Rating

## Bonus Logic
Bonus % is determined by:
- Department
- Performance Rating

> **Bonus Amount = Salary × Bonus %**  
> **Total Pay = Salary + Bonus**

These were calculated using DAX in Power BI.

## Dashboard Highlights
- Gender distribution by department and region
- Average salary by gender
- Salary compliance with $90,000 regulation
- Salary band distribution
- Total bonus paid by region
- Rating vs bonus pattern by segment

##  Files Included
- `Palmoria_HR_Analysis.pbix` (Power BI report)
- `Palmoria Group Bonus Rules.xlsx` (joined in Power BI)
- Optional: `Cleaned HR Data.xlsx` or exported report

##  Tools Used
- Microsoft Power BI
- Power Query (data cleanup)
- DAX (Bonus % and Total Pay)
- Custom visuals (bar, pie, KPI cards, slicers)

##  Author
Jubril Jennifer  
[GitHub Profile](https://github.com/jubriljennifer)
