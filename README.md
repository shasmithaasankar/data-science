## ASSIGNMENT-LAB INTRODUCTION

# AIM
To apply row and column indexing using .loc and .iloc methods in Pandas to filter specific data from a dataset based on given conditions.

# Explanation
In this activity, we use Pandas, a Python library for data manipulation, to filter rows and select specific columns from a dataset containing information about bank clients.
We use the .loc method to apply conditional filtering based on column values. Some key filtering operations include:

-- Selecting clients based on education level and deposit subscription status
-- Filtering clients based on loans, previous marketing outcomes, and employment status
-- Extracting specific columns like name and salary (balance) for clients under a certain age


# Algorithm  

Step 1: Load the dataset using Pandas.  
Step 2:  Inspect the dataset by checking the first few rows and column names.  
Step 3:  Apply filtering conditions using the .loc method:  
   - Select rows where clients with primary education have subscribed to a deposit.  
   - Select rows where clients have not subscribed to a deposit.  
   - Select rows where subscribed clients have a housing or personal loan.  
   - Select rows where secondary-educated clients have not subscribed to a deposit.  
   - Select rows where clients subscribed due to a successful marketing campaign.  
   - Select rows where unemployed clients have not subscribed to a deposit.  
   - Select columns 'age' and 'balance' where age is less than or equal to 30.  
Step 4:  Display the filtered results.  
Step 5:  Save or export the filtered data if needed.
