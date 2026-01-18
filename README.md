# AI Job Market Analysis (2025)

## Project Overview
Analysis of 15,000 AI job listings from 2025 to understand job demand and salary drivers, with a focus on experience level and company location.

## Key Questions
- Which AI job titles are most in demand in 2025?
- What factors most strongly influence AI salaries?

## Key Insights
- Most in-demand roles include **Machine Learning Researcher**, **AI Software Engineer**, **Autonomous Systems Engineer**, and **Machine Learning Engineer**
- **Experience level** is the strongest predictor of salary  
- **Company location** has a major impact on pay  
  - Higher-paying countries include Switzerland, Denmark, and Norway  
  - Lower-paying countries include India and China  
- Job title alone has less influence compared to experience and location

## Modeling Results
- Linear regression model built to estimate AI salaries
- **R² ≈ 0.81**, explaining about 81% of salary variation
- Average prediction error is approximately **$19,000**

## Tools Used
- R
- dplyr
- ggplot2
- caret

## Visualizations

### Salary Distribution
![Salary Distribution](images/Salary%20distribution%20histogram.png)

### Salary by Experience Level
![Salary by Experience](images/Salary%20by%20experience%20(violin%20plot).png)

### Salary by Country
![Salary by Country](images/Salary%20by%20country%20(boxplot).png)

### Top AI Job Titles
![Top AI Jobs](images/Top%20AI%20jobs%20bar%20chart.png)

## Takeaway
This project demonstrates how data analysis and modeling can uncover meaningful trends in the AI job market and explain salary differences across roles, experience levels, and countries.
