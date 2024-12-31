# Practical-Assignment-Module-11
This repository contains files related to ML and AI professional training program Practical Application Module 11

The repository covers the business requirement for a project to  understand what factors make a car more or less expensive and analyse the result. 

Based on analysis, we need to provide clear recommendations to our client—a used car dealership—as to what consumers value in a used car.

This project contains a Jupyter Notebook that contains the analysis using panda dataframe, statistics to explore the data, data minning techniques, sklearn library to use linear regression library annd different types of modelling technique. 

In this project we followed the standard process for data projects called CRISP-DM and tasks are defined for each process involved in CRISP-DM framework. 

- In brief referring to CRISP-DM framework all porocess are covered and tasks are defined while building the project. 


# Findings
In the analysis it was identiifeid that there are different factor that affect the cost of used car. 
  - We find fuel feature has impact on increasing the cost of used price and diesel makes the used car more expensive
  - Number of Cylinders in the used car also makes the car more expensive. In this case 8 cylinder car is the expensive one. 
  - There are impacts on price of used car based on its age(current year - yaer in which car was manufatured). Also the transimisison mode has influenced in the price of the used car. Automatic transmission mode makes car price higher.
  - Type of the car also influence the price of used car. It is observed that if used car is SUV then it has higher cost.
  - The numeric data like odometer and year has strong positive correlation with price.
  - Drive also influence the cost of used car. 4 wheel drive is costly that rear wheel drive.
  - For used car it is also important to impact the cost looking at its condition.
  - Size does not have huge impact on price so that column was dropped.      
  
From all analysis we can understand that key factors that makes the car more or less expensive are - fuel, cylinders, odometer reading, age of the car, transimision mode, drive, condition and type of car.

It is also observed that modelling techiques build using polynomial feature for multiple linear regression gives the best model when used for degree 12 including all key features. 

# Recomemndation for Client
Based on analysis the recommendation we can give to client on used car are - 
- Look for car condition 
- Look for car age 
- Compare the car odometer reading with the manuafacturing year of the car
- if he or she has less budget then can consider car with 4 cylinders as it gives good balance of power and fuel.


The Jupyter Notebook with details on investigation and findings can be find  here: https://github.com/PoojaSinha8809/Practical-Assignment-Module-11/blob/main/prompt_II.ipynb

