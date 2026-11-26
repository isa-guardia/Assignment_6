# Assignment 6: Descriptive Statistics
This repository includes the code for assignment 6 contained in a Jupyter notebook and the requirements to run the code

## Repository contents
- main.ipynb: Jupyter notebook containing the refactored Milestone 1 script which pulls data from the web and creates a Pandas dataframe
    - It then creates a table listing descriptive statistsics of the dataset
    - Creates a bar chart, scatter plot, and pie graph as directed

## Methodology 
This project uses a similar framework to Milestone One for the data processing
### Part One: Minor Refactor
1. URL's for the JSON and CSV files from web containing patient data are defined under unique variable names to be accessed later
2. Create eGFR calculator based on constants and standards for each sex
3. Access JSON and CSV files containing patient data and organizes it into rows
4. Join patient data from the two files using the patient_id, calculate eGFR for each patient and assign it to them, calculate BMI
5. Filter down to patients with an eGFR <= 65 and creates a list
6. Creates a Pandas dataframe from this list
### Part Two: Descriptive Statistics
7. Create a descriptive statistics table with key characteristics of age, height, and weight
8. Create a bar chart with average eGFR per BMI category
9. Create a scatter plot of patient age vs. eGFR
10. Create a pie chart describing patient sex 

## How to Run Notebook
In the terminal, install the required packages using "pip install -r requirements.txt", open the Jupyter noteboook "main.ipynb", run all cells in the notebook