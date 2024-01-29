# AYA_BELAIDI_ShAI
In the scope of registration for the training provided by the SHAI Club for AI in the field of automated learning and artificial intelligence, I solved this task that requires a study of a group of data for employees in the United States of America and extracting the results of this study.
Summary Report
1. Basic Data Exploration:

-The dataset contains 148,654 rows and 13 columns.

-Data types include integers, floats, and objects.

-Missing values were identified in columns 'BasePay', 'OvertimePay', 'OtherPay', 'Benefits', 'Notes', and 'Status'.

2. Descriptive Statistics:

-Mean BasePay: 74,327.50, with a minimum of -166.01 and a maximum of 319,275.01.

-Mean OvertimePay: 66,325.45, with a minimum of -0.01 and a maximum of 245,131.88.

-Mean OtherPay: 5,066.06, with a minimum of -7,058.59 and a maximum of 400,184.25.

-Mean Benefits: 3,648.77, with a minimum of -33.89 and a maximum of 96,570.66.

-Mean TotalPay: 25,007.89, with a minimum of -618.13 and a maximum of 567,595.43.

-Standard deviation for BasePay: 42,912.86.

3. Data Cleaning:

-Dropped 'Notes' and 'Status' columns due to all NaN values.

-Filled missing values in 'BasePay' and 'Benefits' with their respective means.

4. Basic Data Visualization:

a. Created histograms and bar charts to visualize the distribution of salaries.

-The observed histogram pattern, where the frequency of salary decreases as the salary increases, is indicative of a right-skewed distribution.

-The rightward skewness suggests that a majority of employees have lower to moderate salaries, while fewer employees receive higher salaries.

-The peak around 0 salary may indicate a substantial number of employees who might be volunteers, interns, or individuals not receiving a regular salary.

-The two peaks around 15000 persons with a salary close to $100,000 may represent a significant employment category or standard salary level within the organization.

b.Used pie charts to represent the proportion of employees in different departments.

-The largest portion of employees, comprising 22.6%, holds the job title of "Transit Operator." This suggests that a significant portion of the workforce is involved in transportation-related roles.

-Among the top 10 job titles, "Patient Care Assistant" holds the smallest proportion with only 6.2%. This might suggest that roles related to patient care assistance are relatively less common compared to other job categories.

5. Grouped Analysis:

Grouped the data by 'BasePay' and calculated summary statistics for 'OvertimePay', 'OtherPay', 'Benefits'. Compared the average salaries across different groups.

-Negative 'BasePay' values are present, indicating potential anomalies or specific job roles that might have deductions. -The presence of zero values in 'OvertimePay' and 'OtherPay' for some 'BasePay' levels suggests that certain roles may not have overtime or additional pay components. -The 'Benefits' column indicates the average benefits associated with each 'BasePay' level.

6.Simple Correlation Analysis:

-Identified a strong positive correlation (0.95) between 'TotalPay' and 'BasePay'. Visualized the relationship using a scatter plot.

-The plot depicts a clear trend where higher 'BasePay' values are associated with increased 'TotalPay'. Each data point on the scatter plot represents an individual in the dataset, and the positioning of points reveals the simultaneous increase in 'BasePay' and 'TotalPay'.

-The scatter plot illustrates a positive correlation between 'BasePay' and 'TotalPay,' indicating that as 'BasePay' increases, 'TotalPay' also tends to increase.

-The slope of the scatter plot trendline is upward, reflecting the positive relationship between the two variables. -This pattern suggests that a substantial portion of an employee's overall pay, as represented by 'TotalPay,' is influenced by their 'BasePay.'

Recommendations :

-Further investigation is needed into negative values in 'BasePay'.

-Consider exploring the distribution of salaries within specific departments.

-Investigate the factors influencing the strong correlation between 'TotalPay' and 'BasePay'.

-Continue exploring relationships between other variables for a more comprehensive understanding.

*Done by Aya Belaidi in 29 Jan 2024 *
