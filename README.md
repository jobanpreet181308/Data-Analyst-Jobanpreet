
# Descriptive Analysis 
# Project Description: 
Descriptive Analysis of issued building permits patterns in city of Vancouver. 
# Project Title: "Exploring Construction Trends: A Descriptive Study of 2023 &2024 Building Permits in Vancouver"
This analysis aims to explore the building permits issued in Vancouver in 2023, focusing on construction types. The goal is to identify trends in construction and generate valuable insights that can impact the city’s development.
# Dataset: 
The dataset includes issued building permits from year 2023 & 2024 data from the city of Vancouver Each entry in the dataset represents one permit and contains the following important information. Here's a description of all 20 columns in the dataset:
- PermitNum: The unique permit number  for each building permit issued.
-  PermitNumCreatedDate: The date when the permit number was created in the authority’s system.
-  IssueDate: The date when the permit was issued.
- 	PermitElapsedDays: The number of days between the creation of the permit and issue of permit.
- 	ProjectValue: The estimated project value of the project in dollars.
-  TypeOfWork:the type of work for which permit is issued, such as demolition, addition, alteration, or salvage.
- 	Address: The address of the building where the work is being conducted.
- 	ProjectDescription: A detailed description of the work for which permit is issued .
- 	PermitCategory: The classification of the permit, indicating whether the project is commercial, residential, or industrial.
-  Applicant: The name of the person or company applying for the permit.
- 	ApplicantAddress: The address of the applicant applying for the project permit.
- 	PropertyUse: The proposed use of the property, such as retail, manufacturing, or residential.
- 	SpecificUseCategory: A more specific description of the property’s use 
- 	BuildingContractor: The name of the company or contractor applying the building permit.
- 	BuildingContractorAddress: The address of the building contractor.
- 	IssueYear: The year in which the permit was issued.
- 	GeoLocalArea: The geographical area or neighborhood where the project is located within Vancouver.
- 	Geom: The geographical coordinates, for the location of the project for mapping.
- 	YearMonth: The year and month when the permit was issued, 
- 	geo_point_2d: The geographical coordinates (latitude and longitude) .
# Methodology:
# Data Collection and Preparation:
# Data Source: 
We collected records of building permits issued in Vancouver for the year 2023 & 2024
# Tools Used:
- 	Amazon S3: Stored both the original and cleaned datasets for easy access.
- 	AWS Glue DataBrew: Used this tool to clean and prepare the data, fixing any missing information and ensuring everything was accurate.
- 	Amazon Athena: Ran SQL queries to organize the data in a way that made it easier to analyze.
# Descriptive Statistics:
# 1.	Key Metrics Calculated:
-  Number of Permits Issued: Counted how many building permits were issued in 2023.
-  Number of new buildings : counted the number of permits issued for new buildings
# 2.	Data Visualization and Presentation:
- 	Bar Chart: Displayed the types of permits issued, such as new buildings or renovations.
- 	Time-Series Graph: Showed how many permits were issued each month to spot any trends.
- Pie Chart: Illustrated the percentage of project values in different categories like residential or commercial.
# Analysis of Permit Categories:
- 	Divided the permits into groups based on  the type of building mainly new buildings .
# Insights and Findings:
- 	Peak Periods: Identified the months when the most permits were issued, showing when construction was busiest.
- 	Project Value Trends: Noted if spending on certain types of projects was going up or down.
# Recommendations:
- 	Process Efficiency: Suggested ways to streamline the permit process to make it faster and smoother.
- 	Market Insights: Gave advice to city planners and developers on where to focus their efforts based on our findings.
- 	Policy Adjustments: Proposed changes to building rules or regulations based on what we learned from the data.
 
# Tools and Technologies:
 
# AWS Services Used:
1.	Amazon S3: For storing raw and processed datasets with scalable access in various folders.
2.	AWS Glue Data Brew: For automating data cleaning and preparation.
3.	Amazon Athena: To run SQL queries and perform descriptive analysis.
4.	Amazon GLUE : To generate visual ETL .
5.	AWS Lambda: For automating data workflows such as ETL tasks in the data pipeline.
6.	AWS Glue Data Catalog: To organize metadata for easy querying and data discovery.
7.	AWS IAM (Identity and Access Management): For secure access control to AWS services and resources.
8.	AWS Key Management Service (KMS): For encrypting data in S3, ensuring data security and compliance.
# Deliverables:
1.	Comprehensive Analysis Report:
o	Detailed findings and statistical insights into business licensing trends, with recommendations for future policy and business support.
2.	Visual Reports and Dashboards:
	Interactive graphics illustrating trends and distributions, aiding in easy data interpretation.
3.	Stakeholder Presentation:
	A focused presentation outlining critical insights and strategic recommendations for city officials and other stakeholders to aid in decision-making processes.
# Conclusion:
This analysis using AWS tools provides a deep dive into the dynamics of business licensing in Vancouver, highlighting how different business sizes fare over time and suggesting ways to enhance support for smaller enterprises and improve overall business sustainability. For those interested in learning more about data visualization techniques or AWS tools, resources like AWS’s own training modules or data visualization courses on platforms like Coursera could be very beneficial.


