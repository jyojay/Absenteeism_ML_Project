# Absenteeism_ML_Project
Predicting Absenteeism using Logistic regression

## Table of Contents

- [Repository Folders and Contents](#Repository-Folders-and-Contents)
- [Link to Tableau Visualization](#Link-to-Tableau-Visualization)
- [Background and Details](#Background-and-Details)
  
## Repository Folders and Contents
- Absenteeism_Preprocessing.ipynb --> Jupyter notebook code for preprocessing data
- Absenteeism_Machine Learning.ipynb --> Jupyter notebook code for creating ML model
- Absenteeism_Integration.ipynb --> Jupyter notebook code for integrating and reusing ML model
- absenteeism_module.py --> Python module for using pickled model and preprocessing new data
- Absenteeism_data.csv --> Initial data csv
- Absenteeism_preprocessed_final.csv --> Preprocessed data csv output
- model --> Pikled model
- scaler --> Pickled scaler
- Absenteeism_new_data.csv --> New data csv
- Absenteeism_predictions.csv --> Predictions csv
- Absenteeism Analysis.twbx --> Tableau code for visualizing and analyzing new data preidictions
  
## Link to Tableau Visualization
- **https://public.tableau.com/app/profile/jyotsna.jayaraman/viz/AbsenteeismAnalysis_17011283466050/AbsenteeismDashboard**

## Background and Details
The exercise addresses absenteeism at a company during work time. 
The problem is that the business environment of today is more competitive than it used to be, this leads to increased pressure in the workplace. Therefore, it is reasonable to expect that unachievable business goals, and an elevated risk of unemployment can raise people's stress levels. Often, the continuous presence of such factors becomes detrimental to a person's health. Sometimes, this may result in minor illness, which of course, is not desired. However, it may happen that the employee develops a long-term condition, an example being depression. That being said, since we will be solving the problem from the point of view of the person in charge of productivity in the company, we won't focus on that facet of the problem. Rather, we'll look at predicting absenteeism from work, more precisely, we would like to know whether or not an employee can be expected to be missing for a specific number of hours in a given workday? Having such information in advance can improve our decision-making. By reorganizing the work process in a way that will allow us to avoid a lack of productivity, and increase the quality of work generated in our firm. 
Here's how we'll define absenteeism:
"The absence from work during normal working hours, resulting in temporary incapacity to execute regular working activity."
"Based on what information should we predict whether an employee's expected to be absent or not?
How would we measure absenteeism? Should we rather think about trying to predict excessive absenteeism?"
We will answer these and other questions, as we proceed with our analysis. The purpose of the business exercise will be to explore whether a person presenting certain characteristics is expected to be away from work at some point in time or not? In other words, we want to know for how many working hours an employee could be away from work, based on information such as how far they live from their workplace? How many children and pets they have? etc.
### Steps conducted:

### Step 1: Preprocessing the Data
  
### Step 2: Evaluate the Model and Save

### Step 3: Model Integration and use with New Data

### Step 3: Tableau Visualization of Predictions
