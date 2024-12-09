**DATA WRANGLING**

**Project description:** Data wrangling for reports received by the students and employees at UCW.

**Project title:** data wrangling for resolution of reports at UCW.

Objective: the primary goal of this project is to perform comprehensive data wrangling to prepare a robust dataset for employee violation reports at UCW. By cleaning, transforming, and consolidating data from AWS services, the project aims to enhance the accuracy and usability of reports for subsequent analysis and reporting.

**Background:** UCW has human resource department, from the last 6 months they are getting reports on violation. They collected the witnesses list as well. Now they start working on that project.

**Dataset:** the data wrangling process will involve various datasets, including:

o	Violation id - it's a unique id to find the reports

o	Student id - the student who gave the report

o	Name - name of the reporter

o	Violation type - what kind of violation is it?

o	Date of violation - which day this violation has occurred

o	Resolution date - the final resolution day

**Methodology:**

**1-	Data collection:**

I chose this domain to work on this project. Based on these policies I took some sample datasets.

Https://www.ucanwest.ca/wp-content/uploads/2023/07/ucw-procedure-8001p-respectful-workplace-2023-06-28.pdf

**2-	Data assessment:**

o	Conducted an initial assessment of the data quality to identify issues such as missing values, duplicates, and inconsistencies across different datasets by using AWS data brew service in AWS.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/96032212-2185-4a6c-bd4c-a83ea6c1b7fb">

**3-	Data cleaning:**

<img width="468" alt="image" src="https://github.com/user-attachments/assets/0ba3cd6c-3ee1-4744-b8b7-8c27b623ef9f">

o	Addressed missing values through appropriate methods and after cleaning part is done, the results are stored back in s3 in transformed bucket (system).

o	Remove duplicate records and correct inconsistencies in data by preparing recipes.

**4- Data transformation:**

<img width="468" alt="image" src="https://github.com/user-attachments/assets/d8769eed-32f6-4035-b8ec-b10cbb1dcd67">

Perform data type conversions to ensure that all fields are in suitable formats for analysis (e.g., converting strings to datetime objects).
Aggregate data as necessary to ensure that it aligns with the intended analysis.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/d4bc993b-7c1f-481b-bdc3-152a8a1c57c7">

**Tools and technologies:**

o	AWS s3 - AWS data brew - AWS glue.

**Timeline:**

•	Expected completion of the project: 10 weeks, including phases for assessment, cleaning, transformation.

This data wrangling project aims to establish a high-quality dataset that enables UCW to conduct effective resolution for the violations, ultimately enhancing strategies, and completely eradicate the violations at workplace or universities.











