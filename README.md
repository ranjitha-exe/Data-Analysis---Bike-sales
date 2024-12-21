# Bike Sales- Data Analysis (Interactive Dashboard creation using MS Excel)
## Project Objective
Analysis of a data set across different regions to determine how customer age, commute distance and income affect has influenced the sales. 
## Dataset used
-<a href="Data Set- bike sales.xlsx">Bike Sales Data</a>
## Questions
- How does income affect the bike purchases?
- Compare the demographic of bike purchases.
- How does customer commute influence the sales?
- Dashboard interaction <a href="Dashboard.png"> View Dashboard</a>
## Data Analysis Process
 **1. Data Cleaning**:

a. Duplicate Removal: Checked the Excel dataset for duplicates and removed all duplicate rows to ensure data accuracy.  

b. Field Standardization:   
      
- Replaced values in the Marital Status field: changed "M" and "S" to "Married" and "Single" for consistency.  
- Updated the Gender field: replaced "M" and "F" with "Male" and "Female" for clarity.  

       
**2. Data Formatting**:  
  - Adjusted the formatting of the Income field to ensure consistent numeric or currency representation.

    
**3. Feature Engineering**:  
 - Created a new column, Age Bracket, using the formula:  

         ### =IF(L2>65, "Senior", IF(L2>54, "Middle Age", IF(L2>=31, "Adults", IF(L2<31, "Adolescent", "Invalid"))))`

This categorized individuals into appropriate age brackets: Senior, Middle Age, Adults, and Adolescent.  


- Updated the Commute Distance field by rephrasing "10+ miles" to "more than 10 miles" for better readability and proper data ordering.

  
**4. Data Analysis**:
  
- Created pivot tables to analyze relationships and generate insights:
  
    - Average Income vs. Bike Purchases by Gender.
    - Commute Distance vs. Bike Purchases.
    - Age Bracket vs. Bike Purchases.

  
**5. Dashboard Creation**:
    
- Designed a dashboard by merging charts created from the pivot tables:
- Included line graphs to visualize key insights such as:
          - Average income distribution based on bike purchases and gender.
          - The relationship between commute distance and bike purchases.
          - Age bracket trends in bike purchases.
- Used slicers and filters in Excel to make the dashboard interactive and user-friendly.
## Dashboard
![Dashboard.png](https://github.com/ranjitha-exe/Data-Analysis---Bike-sales/blob/main/Dashboard.png)


