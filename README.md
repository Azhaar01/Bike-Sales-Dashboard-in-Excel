# **BIKE SALES DASHBOARD IN EXCEL**

**I did 3 steps in this project:**
1. Data cleaning:

   1.1 I used Find and replace to change M and S in marriedarital Singlestatus column and make more clear 
       M >> married 
       S >> Single 
       And Gender Column 
       F >> Female 
       M >> Male 

   1.2 Income column I change its type from general to currency

   1.3 I changed the values of the age column from specific numbers to ranges how? I made a new column called age-brackets and I wrote a formula
       == IF(L15< 54, “Old” , IF(L15>=31, “Middle Age”, IF(L15<31, “Adolescent”, “Invalid”)))  

   1.4 I changed the name of marriedarital Singlestatus column to Marital Status to make it meaningful 

3. Build a pivot table
4. Build a Dashboard
