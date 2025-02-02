# Full-Data-Analysis-Project-using-SQL-And-PowerBI
This SQL script is designed to clean, standardize, and analyze HR data. Once the data is analyzed it visualizes the results using PowerBI

## Step 1: Data Cleaning and Preparation 
  1. Fixed Column Naming Issues 
  - Renamed the id column to emp_id to resolve encoding issues.
 
2.  Standardized Date Formats 
   - Converted birthdate, hire_date, and termdate from inconsistent string formats (MM/DD/YYYY, MM-DD-YYYY) to YYYY-MM-DD.
   - Ensured these columns were stored as proper DATE types.
     
 3.  Calculated Employee Age 
   - Added an age column and populated it based on birthdate.

     ## Step 2: Data Analysis 
  1. Demographic Analysis
   - Examined the gender and race distribution of active employees.
   - Analyzed age demographics, including the youngest and oldest employees and the number of employees under 18.
 
  2.  Workforce Distribution 
   - Investigated how employees were spread across headquarters and remote locations.
   - Identified job title distributions across the company.
     
  3.  Employee Tenure & Turnover
   - Measured the average length of employment for terminated employees.
   - Determined which department had the highest turnover rate.

      ## Exporting and Visualizing the Results
  1.  Saved the SQL Query Results to a CSV File
   - Exported the cleaned and analyzed data into a CSV file.
     
  2. Created a Power BI Dashboard
   - Imported the CSV file into Power BI.
   - Designed visualizations such as bar charts, pie charts, and trend lines to present insights on workforce demographics, employee turnover, and hiring trends.

