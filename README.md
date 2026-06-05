# The Task  
## HR Dashboard – Workforce Trends & Hiring Patterns  
Business Context  
The company wants to track workforce growth, hiring trends, and department growth over time. The dashboard should focus on hiring trends.  

My solution to the project can be found on Tableau Public https://public.tableau.com/app/profile/yvette.dezso/viz/YvetteDezsM2S1AdventureWorksHRDashboardDec2025/HRSummary


## Key Focus Areas  
1. Employee Growth: Track headcount trends over time.  
2. Hiring Patterns: Identify hiring peaks and low periods.  
3. Department Growth: Analyze which departments have grown the most.  

## Key Questions to Explore
1. Has the total employee count increased or decreased over time?  
2. Which years saw the highest hiring activity?  
3. How does hiring vary across departments?  

## KPIs to Consider  
1. Total Employee Headcount (How many employees are currently active?)  
2. New Hires Per Year (Are there hiring spikes in certain years?)  
3. Department-Wise Employee Distribution (Which departments have grown the most?)  

## Hints for Implementation  
Use tc-da-1.adventureworks_db_v19.Employee to track HireDate trends over time.  
Group hiring trends by year using EXTRACT(YEAR FROM HireDate).  
Check tc-da-1.adventureworks_db_v19.EmployeeDepartmentHistory to analyze department-level growth.  
