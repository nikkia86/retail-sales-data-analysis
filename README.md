# Retail Sales Data Analysis

## Project Overview
This project explores a retail sales dataset to identify patterns in weekly sales and understand how sales vary across stores, departments, store types, holiday periods, and promotional markdowns. The analysis is presented in a Jupyter Notebook and uses exploratory data analysis (EDA) techniques to summarise the data and highlight key insights.

## Business Objectives
The objectives of this analysis are to:
- Understand the distribution and variation of weekly sales
- Compare sales performance across stores and departments
- Identify whether holiday weeks impact weekly sales
- Explore the relationship between promotional markdowns and weekly sales
- Compare average weekly sales across store types
- Visualise overall weekly sales trends over time

## Analytical Questions
This analysis seeks to answer the following questions:
- How do weekly sales vary across different stores and departments?
- Are there observable differences in weekly sales during holiday and non-holiday periods?
- Do promotional markdowns have a noticeable relationship with weekly sales?
- How do average weekly sales compare across different store types?
- What trends or fluctuations are visible in total weekly sales over time?


## Dataset
Source: Kaggle Retail Dataset by Manjeet Singh  
Kaggle link: https://www.kaggle.com/datasets/manjeetsingh/retaildataset

The dataset contains multiple files (for example, sales, stores, and features) and includes fields such as:
- Store
- Dept
- Date
- Weekly_Sales
- IsHoliday
- Store Type and Size
- MarkDown variables (MarkDown1 to MarkDown5)

## Tools and Technologies Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook (VS Code)
- Git and GitHub

## Project Structure
Typical structure in this repository:
- `jupyter_notebooks/`
  - `retail_sales_analysis.ipynb`
- `data/`
  - dataset CSV files used in the analysis
- `README.md`

## Methodology
The analysis was conducted using a structured exploratory data analysis approach. The datasets were first loaded and inspected to understand their structure, data types, and completeness. Data cleaning steps were applied to handle missing values and ensure consistency across datasets. Descriptive statistics and grouped summaries were then used to compare weekly sales across stores, departments, store types, and holiday periods. Visualisations were created to examine overall sales trends over time and to support interpretation of key patterns observed in the data.


## Key Analysis Steps
The notebook includes the following analysis steps:
- Initial data exploration (shape, columns, missing values, sample rows)
- Descriptive statistics for weekly sales
- Average weekly sales by store
- Average weekly sales by department
- Total weekly sales trend over time (line chart)
- Holiday vs non holiday weekly sales comparison
- Correlation between total markdowns and weekly sales
- Average weekly sales by store type


## Key Findings Summary
The analysis revealed substantial variation in weekly sales across stores and departments, indicating differences in performance and customer demand. Holiday weeks were associated with higher average weekly sales compared to non-holiday periods. Total weekly sales over time showed noticeable fluctuations, with certain periods experiencing significant increases. The correlation analysis indicated a very weak relationship between promotional markdowns and weekly sales, suggesting that markdowns alone do not strongly drive sales changes. Among store types, type A recorded the highest average weekly sales, followed by types B and C.


## How to Run This Project Locally
1. Clone the repository from GitHub
2. Open the project folder in VS Code
3. Ensure you have Python installed and select a Python environment
4. Install dependencies if required (for example: pandas and matplotlib)
5. Open and run the notebook:
   - `jupyter_notebooks/retail_sales_analysis.ipynb`

## Deployment
This project is submitted with:
- A GitHub repository link (source code)
- A live deployed link (as required by the submission procedure)

Deployment can be completed using a platform such as Heroku by connecting the GitHub repository and deploying the selected branch. The repository should include any required deployment files based on the platform used.

## Use of AI Tools
ChatGPT was used during the development of this project to support learning and productivity. This included:
- Clarifying Python and pandas concepts
- Debugging errors and improving code structure
- Drafting and refining README documentation and markdown explanations in the notebook

All final decisions, edits, and validation of results were reviewed by the author to ensure the analysis reflects the outputs produced in the notebook.

## Author
Adenike Adeyanju
