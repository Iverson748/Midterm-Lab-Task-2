# Midterm-Lab-Task-2
##  Midterm Lab Task 2 - Data Cleaning and Transformation Using Power Query Editor
## Step 1 - Cleaning the data using PowerQuery Editor
Download and open the raw data given by your instructor.

Add the required columns (Min Sal, Max Sal, Role Type).

Split the columns (Salary Estimate, Location, Size).

Change the columns to appropriate data types.

Filter columns .

Remove unnecessary columns to avoid redundancy .

Save the M Language to a notepad.

Before Cleaning
Uncleaned Photo 1

![Image](https://github.com/user-attachments/assets/5efe1018-2ce7-4e40-8c9a-0dde85dddc59)
 Uncleaned Photo 2
 
![Image](https://github.com/user-attachments/assets/e1ebc394-b25a-46be-bf46-ccad1cd37afa)

Uncleaned Photo 3

![unc3](https://github.com/user-attachments/assets/15f3aa79-e7ab-4f60-81c3-40bb8d8cc0d5)

## After Cleaning

Cleaned Photo  1

![clean1 1](https://github.com/user-attachments/assets/0e306f12-0318-437f-833a-998a537d3680)



Cleaned Photo 2

![clean2 2](https://github.com/user-attachments/assets/18cfbbc2-6cad-4577-b21b-5b4f679c0492)


Cleaned Photo 3

![cleaned2 3lst](https://github.com/user-attachments/assets/30a6d45b-df44-480a-a0d8-dc1c3ef78b56)


M Language

![m la](https://github.com/user-attachments/assets/cec57896-3bd2-4299-939a-2b6933742b9e)


## Step 2 - Reshaping and Grouping the Tables
Duplicate and reference Unclean DS Jobs to create new queries (Sal By Role Type dup, Sal By Role Size ref, Sal By State ref).

Select appropriate columns 

Change the columns to required data types (Currency).

Multiply Min Sal and Max Sal by 1000.

Group data by Role Type, Size, State Full Name to get averages.

Merge State Mapping with Unclean DS Jobs using State Abbreviation.

Rename merged column to State Full Name and remove nulls.

Check and review Query Dependencies.

## Grouped of Tables
Salary by Size Role Type Table


![role size](https://github.com/user-attachments/assets/08b04a29-c82c-4960-99ac-3cfaac99721b)

Salary by Role Type Table


![role type](https://github.com/user-attachments/assets/d2a530bb-4cd1-4e5c-bfe1-608d22e34cc8)


Salary by State Table

![sal by states](https://github.com/user-attachments/assets/d1298da2-d48d-4b6d-a828-5259425c3e34)



States Mapping Table

![states](https://github.com/user-attachments/assets/d837f248-7887-4e4a-970e-0d2111794871)


 View and selecting the Query Dependencies.
Double check if they are properly linked appropriately.

Photo of Query Dependencies
![Depencies](https://github.com/user-attachments/assets/6f226dfb-c995-4066-9a03-3004db22ac1c)
