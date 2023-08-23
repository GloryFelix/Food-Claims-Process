# Food-Claims-Process
This project is carried out as part of the requirement that got me certified as a data a Data Analyst Associate by Datacamp.

## Introduction
The aim of this project is to exhibit my skills in exploratory analysis, data visualization and communication.

## BackGround
Vivendo is a fast food chain in Brazil with over 200 outlets.
Customers often claim compensation from the company for food poisoning.
The legal team processes these claims. The legal team has offices in four locations.
The legal team wants to improve how long it takes to reply to customers and close claims.
The head of the legal department wants a report on how each location differs in the time it
takes to close claims.

## Task 1:
For every column in the data:
- State whether the values match the description given in the table above.
- State the number of missing values in the column.
- Describe what you did to make values match the description if they did not match.

**Claim ID:** The column matched the description. They are non-missing values. The values are unique. No changes were made in this column.

**Time to Close:** The column matched the description given. They were non missing values. No changes were made in this column.

**Claim Amount:** The column do not exactly matched the description given. They were non-null missing values. The data type is changed to the one given in the description. 

**Amount Paid:** They were 36 missing values in this column. The missing values were replaced with the median value of the column.

**Location:** They were non-missing values. The column has four(4) that matches those in the description. They were non-missing values.No changes were made in this column.

**Individuals on Claim:** The  column matched the description. They were non-missing values. No changes were made in this column.

**Linked Cases:** They were 26 missing values which is replaced with the False value as described.

**Cause:** Non-missing values. The values in this column are not consistent(Meat,meat, unknown, vegetables and VEGETABLE), the "Meat" values are changed to "meat" and "VEGETABLES" to "vegetable".

## Task 2:
Create a visualization that shows the number of claims in each location. Use the visualization to:
- State which category of the variable location has the most observations
- Explain whether the observations are balanced across categories of the variable location.

There are four Locations included in this data which are RECIFE, SAO LUIS,FORTALEZA and NATAL. The most common location is RECIFE, with SAO LUIS being second although with half the number of locations. The categories are unbalanced, most observations are in RECIFE. The legal team should focus on RECIFE location more as they have most claims.

## Task 3:
Describe the distribution of time to close for all claims. Your answer must include a visualization that shows the distribution.

From the graph above, we cand deduct that most claims are closed in less than 200 days. The distribution of the time to close a claim is right skewed. Few claims are closed over 350days. The Legal team should focus on claims that took over 200days and found out why is taking longer compared with those that were closed earlier.

## Task 4:
Describe the relationship between time to close and location. Your answer must include a visualization to demonstrate the relationship.

From the chart above, the team should focus on SAO LUIS with time_to_close of over 500 days. Also, further analysis should be carried out at SAO LUIS to know why it takes more days to claim compared to other location. Further analysis should be done to understand if location really does impact time to claim.

