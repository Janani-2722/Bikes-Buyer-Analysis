# Bikes-Buyer-Analysis

## Overview
This project involves analyzing a dataset related to bike buyers. The dataset contains various attributes such as marital status, gender, income, education, occupation, and whether the individual purchased a bike. The goal is to understand the factors influencing bike purchases and to derive insights that could be useful for marketing strategies.

## Dataset Description
The dataset is provided in an Excel file named `Excel Project Dataset.xlsx`. It contains two sheets:
- **bike_buyers**: Contains raw data with attributes like ID, Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age, and Purchased Bike.
- **Working Sheet**: Contains the same data as `bike_buyers` but includes an additional column called "Age Brackets," which categorizes individuals into "Old Age," "Middle Age," or "Adult" based on their age.

## Data Dictionary
- **ID**: Unique identifier for each individual.
- **Marital Status**: Indicates whether the individual is married or single.
- **Gender**: The gender of the individual (Male or Female).
- **Income**: Annual income of the individual.
- **Children**: Number of children the individual has.
- **Education**: Highest level of education attained (e.g., Bachelors, Partial College, High School).
- **Occupation**: The occupation of the individual (e.g., Skilled Manual, Clerical, Professional).
- **Home Owner**: Indicates whether the individual owns a home (Yes or No).
- **Cars**: Number of cars owned by the individual.
- **Commute Distance**: Distance of commute (e.g., 0-1 Miles, 2-5 Miles).
- **Region**: The region where the individual resides (e.g., Europe, Pacific).
- **Age**: The age of the individual.
- **Age Brackets**: Categorization of age into "Old Age," "Middle Age," or "Adult."
- **Purchased Bike**: Indicates whether the individual purchased a bike (Yes or No).

## Analysis and Insights
- **Age Brackets**: The "Age Brackets" column is calculated using an Excel formula that categorizes individuals based on their age:
  - **Old Age**: Age > 54
  - **Middle Age**: Age between 31 and 54
  - **Adult**: Age < 31
- **Key Insights**:
  - **Income and Bike Purchases**: Individuals with higher incomes are more likely to purchase bikes.
  - **Occupation**: Professionals and skilled manual workers are more likely to purchase bikes compared to clerical workers.
  - **Region**: Individuals in the Pacific region are more likely to purchase bikes compared to those in Europe.
  - **Age**: Middle-aged individuals (31-54) are the most likely to purchase bikes.
