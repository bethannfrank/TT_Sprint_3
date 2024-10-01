# TT_Sprint_3 Statistical Data Analysis
This is a repository for TT Sprint 3 Statistical Data Analysis that analyzes cell phone plan data. The project determines which prepaid plan brings in more revenue for the company.
- This project used independent t-tests to compare whether there were significant differences in revenues between plans, and for a specified location.
- Data was prepared, aggregated, and exploratory analysis conducted prior to the final t-tests.
- The project was built on the Jupyter platform using Python to code, including the Matplotlib library for data visualization and SciPy library for analysis.
- The project was developed by the data science student, reviewed by a project reviewer and final edits made by the students based on the review.

**Results and Conclusions** There were modest differences in some aspects of plan usage (internet usage), likelihood of exceeding plan limits, and average revenue per user for plans A and B. Differences in average revenue per user was statistically significant at the 99% interval level (p=9.43e-15). Locations were compared (NY/NJ vs other locations), with NY/NJ average revenue slightly lower, statistically significant at a 95% interval level (p=0.03). The overall conclusion was there is value in encouraging users to sign up for plan A from a revenue perspective as that will generally result in higher revenue for the company. There would be value in further analyzing customers across other locations, and to analyze revenue vs. churn rates of customers.

Histogram of total revenue for plans:
![image](https://github.com/user-attachments/assets/0670eecd-4f7c-4aa2-b5a9-7137ebb4d31c)

This project uses cell phone data available here: 
- Call data: https://practicum-content.s3.us-west-1.amazonaws.com/datasets/megaline_calls.csv
- Messages data: https://practicum-content.s3.us-west-1.amazonaws.com/datasets/megaline_messages.csv
- Internet data: https://practicum-content.s3.us-west-1.amazonaws.com/datasets/megaline_internet.csv
- https://practicum-content.s3.us-west-1.amazonaws.com/datasets/megaline_users.csv

To run the program, Python 3 (3.11.5) was used with the following libraries: pandas, numpy, math, matplotlib, scipy.

To launch this project on a local machine, the data set should be accessible in the project folder, and python lanched with the above listed packages installed.
