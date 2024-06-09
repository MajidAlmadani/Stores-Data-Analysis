# Stores-Data-Analysis
Fil Superstores, a national level retail company, is looking to leverage data science to understand customer behavior and improve profitability. The company operates multiple warehouses and retail stores across KSA and has provided data from these operations. This project involves exploring the provided data to uncover patterns and relationships that can help in making informed business decisions.


# Data Description
Field	Description
Store ==  ID	A unique ID for every store.
Gregorian Date ==	Date when the data is collected.
Hijri Date ==	Corresponding hijri date.
Day ==	Day of the week in which data is collected.
Greg. Month ==	The Gregorian month in which the data is collected.
Hijri Month ==	The Islamic month in which the data is collected.
Location ==	Store location in the city ('Center', 'Border', 'Outskirts').
Store Size ==	Size of the store ('Grande', 'Hyper', 'Regular').
Parking ==	Total number of cars that can be parked in the store parking.
Mall ==	Is the store inside a mall? (Yes or No).
Work Hours ==	Type of working hours ('24', '12', '18').
Cost/day ==	Average daily operating costs.
Promotion ==	Type of promotion on that day ('Grand', 'Regular', 'None').
Customer Base	== Total number of different customers that have visited the store.
Advertisements ==	Number of regular customers who received promotional messages.
Competition ==	Number of adjacent similar retail stores within a 10 km range.
Customers ==	Number of customers on the given day.
Profit/day ==	Profit made by the store on the given day.


# Tasks and Deliverables
Task 1: Data Preparation
Objective: Clean the data by handling missing values, removing outliers, and fixing inconsistencies.
Methods: Various data cleaning techniques will be used, and the chosen methods will be justified.

Task 2: Pair-wise Plots
Objective: Visualize relationships between all input variables and the profit variable.
Methods: Pair-wise plots using libraries like Matplotlib and Seaborn.

Task 3: Top Numerical Variables
Objective: Identify the top three numerical variables that have the strongest relationship with profit.
Methods: Statistical analysis and correlation methods.

Task 4: Separating Stores
Objective: Determine if input variables can separate low and high-performing stores.
Methods: Visualizations and clustering techniques.

Task 5: Low Performance Patterns
Objective: Identify common patterns among low-performing stores.
Methods: Data analysis and visualization techniques.

Task 6: High Performance Patterns
Objective: Identify common patterns among high-performing stores.
Methods: Data analysis and visualization techniques.

Task 7: Unrelated Variables
Objective: Identify input variables that are not related to profit.
Methods: Statistical analysis and feature importance techniques.

Task 8: Profit Prediction
Objective: Predict the estimated profit per day for proposed new retail stores.
Methods: Machine learning models using all relevant variables except Store ID, Gregorian Date, and Hijri Date.


# Images
# Data after pre-processing
![image](https://github.com/MajidAlmadani/Stores-Data-Analysis/assets/125421977/c4033202-6502-41f5-8907-1b79d695a9e6)

# EDA
![image](https://github.com/MajidAlmadani/Stores-Data-Analysis/assets/125421977/f2f49735-da73-457a-95c4-f859e2615566)
![image](https://github.com/MajidAlmadani/Stores-Data-Analysis/assets/125421977/542891a8-7f56-4d2a-9778-394d081be9aa)
![image](https://github.com/MajidAlmadani/Stores-Data-Analysis/assets/125421977/29791ce5-3170-4de0-9449-9534403e3c67)

# PCA vs Profit/day
![image](https://github.com/MajidAlmadani/Stores-Data-Analysis/assets/125421977/8f1b9cdd-95a7-465c-9744-94146fb49963)

# Non-numerical features vs Profit/Day
![image](https://github.com/MajidAlmadani/Stores-Data-Analysis/assets/125421977/5f162715-0af9-41f2-b715-1277c6dbf1b3)
![image](https://github.com/MajidAlmadani/Stores-Data-Analysis/assets/125421977/b189e76f-869d-4240-8247-2f3302f527c1)
![image](https://github.com/MajidAlmadani/Stores-Data-Analysis/assets/125421977/17756bbd-b7aa-4cb3-9420-9a69e0b39063)

# Fit & Predict & test & compare models with Mean Squared Error
![image](https://github.com/MajidAlmadani/Stores-Data-Analysis/assets/125421977/bb476907-e3d6-4236-89c0-e86ff06ee0f2)

# Predict using the best model
![image](https://github.com/MajidAlmadani/Stores-Data-Analysis/assets/125421977/58407fb5-3cdb-4d3c-a10b-32f41356f2b7)
