# Bike Sales- Data Analysis (Interactive Dashboard creation using MS Excel)
## Project Objective
Analysis of a data set across different regions to determine how customer age, commute distance and income affect has influenced the sales. 
- To identify the target audience.
- Marketing focus areas
- Product strategies
   
## Dataset used
-<a href="Data Set- bike sales.xlsx">Bike Sales Data</a>
## Questions
- How does income affect the bike purchases?
- Compare the demographic of bike purchases.
- How does customer commute influence the sales?
- Dashboard interaction <a href="Dashboard.png"> View Dashboard</a>
## Data Analysis Process
 **1. Data Cleaning**:

a. Duplicate Removal: 
- Checked the Excel dataset for duplicates and removed all duplicate rows to ensure data accuracy.  

b. Field Standardization:   
      
- Replaced values in the Marital Status field: changed "M" and "S" to "Married" and "Single" for consistency.  
- Updated the Gender field: replaced "M" and "F" with "Male" and "Female" for clarity.  

       
**2. Data Formatting**:  
  - Adjusted the formatting of the Income field to ensure consistent numeric or currency representation.

    
**3. Feature Engineering**:  
 - Created a new column, Age Bracket, using the formula:  

          =IF(L2>65, "Senior", IF(L2>54, "Middle Age", IF(L2>=31, "Adults", IF(L2<31, "Adolescent", "Invalid"))))`

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

## Project Insights
**1. Income**
  ![Income insights.png](https://github.com/ranjitha-exe/Data-Analysis---Bike-sales/blob/main/Income%20insights.png)
  
-People with higher income are more likely to purchase bikes.
-For both genders, individuals who purchased bikes had a higher average income compared to those who did not.
-Gender-Based Trends:

    -Males: Have a higher average income compared to females, both among those who purchased bikes and those who did not.
    -Females: Show a similar trend where higher income correlates with a higher likelihood of purchasing a bike.


**2. Customer Demographic**
   ![Customer Age.png](https://github.com/ranjitha-exe/Data-Analysis---Bike-sales/blob/main/Customer%20Age.png)

- Adolescent (age<31) : Both "Yes" and "No" responses are low, indicating limited interest or purchasing power in this age group.
- Adults (age group 31-54) : There is a significant peak for both "Yes" and "No," with a dominant number of "Yes" responses. This suggests that adults are the primary buyers.
- Middle Age (age group 55-65) : A noticeable drop in both "Yes" and "No" responses compared to adults, implying a decline in interest or purchasing behavior.
- Senior (age>65) : Very low responses for both "Yes" and "No," showing minimal engagement from this group.
- People in the **age group of 31-54 years** show the highest interest in buying bikes.


 **3. Commute Distances**
    ![Customer Commute.png](https://github.com/ranjitha-exe/Data-Analysis---Bike-sales/blob/main/Customer%20Commute.png)

- 0–1 Miles: Highest interest, with significantly more "Yes" responses than "No."
- 1–2 Miles: Interest declines sharply and is evenly split between "Yes" and "No."
- 2–5 Miles: Balanced but low interest; responses plateau.
- 5–10 Miles: "No" responses surpass "Yes," showing reduced likelihood of purchases.
- More than 10 Miles: Very low interest, with minimal purchases for long commutes.
- The likelihood of purchasing a bike decreases as commute distance increases.
- **Short-distance commutes (0–1 mile) represent the key market for bike sales.**

**Key Takeaways & Strategic Recommendations**

- **Target Audience**:
    - Adults, particularly those with higher incomes, are the primary target.
    - Males show slightly higher purchase propensity, but females are also a valuable segment.

 **Marketing Focus**:
    - Highlight the cost-efficiency, convenience, and environmental benefits of biking for short commutes.
    - Tailor campaigns to appeal to high-income customers, focusing on premium quality and advanced features.
    - Use gender-neutral marketing strategies to attract both males and females.
    
- **Product Strategies**:
    - Emphasize urban commuter bikes for short distances.
    - Introduce affordable electric or hybrid bikes to attract medium-distance commuters (2–5 miles) and higher-income buyers.
    - Offer comfort and accessibility features for seniors and adolescents.
  
-
  
