# IDS-706 Data Engineering Assignment
## Mini Project : Pandas Descriptive Statistics Script

[![CI](https://github.com/nogibjj/Mini_Project_Pandas_ISL/actions/workflows/hello.yml/badge.svg)](https://github.com/nogibjj/Mini_Project_Pandas_ISL/actions/workflows/hello.yml)

### Requirements
    1. Python script using Polars for descriptive statistics
    2. Read a dataset (CSV or Excel)
    3. Generate summary statistics (mean, median, standard deviation)
    4. Create at least one data visualization

### Deliverables
    1. Python script 
    2. CI/CD with badge
    3. Generated summary report (PDF or markdown) via CI/CD for extra credit or making your own PDF or MD file and pushing it

### Analysis
Dataset : HR.csv (also known as HR Analytics Employee Attrition & Performance)
 - The data used in this analysis was provided by IBM and was originally created to study employee turnover.
 - From the available variables, I specifically focused on the "Age" at retirement.

### Progress
#### Step1. 
Created Github Repository and required files such as Makerfile, requirement.txt, CICD.yml, Dockerfile, devcontainer.json and so on

<Makerfile>
![Makerfile](https://github.com/user-attachments/assets/63956594-f90f-4000-b76d-eceaef59c84e)

<Requirement>
![Requirements](https://github.com/user-attachments/assets/afdaefae-5fd4-4a2e-aac5-a7c2709c717d)

<Yaml>
![yml](https://github.com/user-attachments/assets/74d3b715-fcfd-44ce-88f3-7709501d8d59)

<Docker>
![Docker](https://github.com/user-attachments/assets/a66a694c-1640-4026-8b49-83ab86c22bcd)

<Devcontainer>
![Devcontainer](https://github.com/user-attachments/assets/551ac559-baa9-4420-9cd2-2a8aacf83099)

#### Step2. 
Build a main.py and main_test.py. in 'main.py' this import CSV file(HR.csv) and calculate average, median, and Standard deviation of retired employees. Additionally, plot a histrogram to visualize the age distrubution of the retired employees.

<main.py>
![main](https://github.com/user-attachments/assets/213bba61-2af9-4116-8ea2-d5ebaee3db4f)

<main_test.py>
![test](https://github.com/user-attachments/assets/b3589147-68d2-40e8-a4f2-6545d5f88798)

<Mean, Median, Standard Deviation and Histogram>
<![mean, median, std and histogram](https://github.com/user-attachments/assets/061e19eb-a47b-4b7c-b058-03aa1d2f3552>

#### Step3. 
Verify if the GitHub Action is working properly
<img width="1094" alt="lint, test, format" src="https://github.com/user-attachments/assets/cd8e5ea1-40fc-4790-8087-2434c816916b">


