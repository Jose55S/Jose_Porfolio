Example data science porfolio

# [Project 1: Data Science Salary Estimator: Project Overview](https://github.com/playingNumbers/ds_salary_proj)
* Created a tool that estimates data science salaries (MAE ~ $ 11K) to help data scientists negotiate their income when they get a job.
* Scraped over 1000 job descriptions from glassdoor using python and selenium
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark. 
* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model. 
* Built a client facing API using flask 
 
 
# [Project 2: Data Cleaning](https://github.com/Jose55S/Jose_Porfolio/blob/main/images/How%20to%20clean%20data%20in%20Python.docx)
After scraping the data, I needed to clean it up so that it was usable for our model. I made the following changes and created the following variables:

*	Parsed numeric data out of salary 
*	Made columns for employer provided salary and hourly wages 
*	Removed rows without salary 
*	Parsed rating out of company text 
*	Made a new column for company state 
*	Added a column for if the job was at the company’s headquarters 
*	Transformed founded date into age of company 
*	Made columns for if different skills were listed in the job description:
    * Python  
    * R  
    * Excel  
    * AWS  
    * Spark 
*	Column for simplified job title and Seniority 
*	Column for description length

![](https://github.com/Jose55S/Jose_Porfolio/blob/main/images/data_cleaning_cycle.jpg)

## EDA
I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights from the pivot tables. 

![](https://github.com/Jose55S/Jose_Porfolio/blob/main/images/salary_by_job_title.png)
![](https://github.com/Jose55S/Jose_Porfolio/blob/main/images/positions_by_state.png)
![](https://github.com/Jose55S/Jose_Porfolio/blob/main/images/correlation_visual.png)

# [Project 3: for Coursera - Databases_and_SQL_for_Data_Science](https://github.com/Jose55S/Jose_Porfolio/blob/main/DB0201EN-Week3-1-1-Connecting-v4-py.ipynb)

## Description 
This course teaches a lot of things, since how to run basic queries until modeling databases. 
What was nice about the learnings, is about the exercises using real data!

## Topics
-> Statements: CREATE, DELETE, SELECT, INSERT and UPDATE table.

-> COUNT, LIMIT, DISTINCT.

-> String Patterns, Ranges, Sorting, Grouping.

-> Sub-queries and multiple tables(implicit join)

-> Database access from Python.

-> Analyzing data with Python.

-> JOIN(inner, outer).

-> Working with real-word datasets.

-> Relational databases concepts.

-> Relational Model Constraints.
 
 # [Project 4: Write and Save Files in Python](https://github.com/Jose55S/Jose_Porfolio/blob/main/PY0101EN-4-2-WriteFile.ipynb)
 Writing the text to file in Python Programming Language where you learn know how to write to file and copy the file.
![](https://github.com/Jose55S/Jose_Porfolio/blob/main/images/Screenshot%202021-06-28%20193519.png)

