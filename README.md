# Data Analytics Portfolio

## Data Wrangling Project

Project Title: Data Analytics Platform (DAP) Implementation for Enhanced Recruitment and Selection Procedures at UCW HR Department
#### Objective
The primary goal of this project was to implement a Data Analytics Platform (DAP) to improve the performance of recruitment and selection procedures at the University Canada West (UCW) HR Department. By leveraging AWS services and following a structured data analytics approach, the project aimed to enhance the efficiency, accuracy, and insights derived from recruitment process data.

#### Background
The UCW HR Department had accumulated data from various aspects of the recruitment and selection process, including job applications, candidate assessments, interview records, and onboarding activities. However, this data was often scattered across different systems, making it challenging to derive meaningful insights. The implementation of a DAP facilitated better decision-making and more efficient recruitment procedures.

Dataset
#### The data wrangling process involved various datasets, including:

#### Job Applications: Containing candidate details such as name, date of birth, gender, application date, and applied position.
Candidate Assessments: Information on assessment scores, test results, and evaluations.
Interview Records: Data from interview schedules, feedback, and outcomes.
Onboarding Activities: Records of successful onboarding processes and related activities.
#### Methodology
The project followed a 15-step Data Analytics Platform implementation process:

#### Data Analytical Question Formulation
#### Data Discovery
#### Data Storage Design
#### Test Dataset Generation
#### Data Ingestion
#### Data Storage
#### Data Pipeline Design
#### Data Cleaning
#### Data Structuring
#### Data Pipeline Implementation
#### Data Analysis
#### Data Visualization
#### Data Publishing
#### Data Enriching
#### Data Protection
<img width="748" alt="simraan" src="https://github.com/user-attachments/assets/1ff80213-f1ad-4224-82d2-b46eaf3713d6">

AWS Architecture and Tools
The DAP utilized the following AWS services and components:

Amazon S3: For data storage, with multiple buckets for different stages of data processing.
AWS Glue: For data integration and ETL (Extract, Transform, Load) processes.
AWS Glue DataBrew: For data preparation and transformation.
Amazon Athena: For querying data stored in S3.
Amazon QuickSight: For data visualization and dashboard creation.
Amazon EC2: For hosting custom applications or processing tasks.
The architecture also included:

Data pipelines for the HR Department
Data Catalog for metadata management
Web Server and General Server for hosting applications
#### Key Metrics
The project focused on four types of metrics:

#### Descriptive Metric: Application to Interview Conversion Rate
Data Source: Job Applications
Diagnostic Metric: Candidate Drop-off Rate
Data Source: Candidate Assessments
Predictive Metric: Interview to Hire Conversion Rate
Data Source: Interview Records
Prescriptive Metric: Onboarding Efficiency Index
Data Sources: Onboarding Activities
#### Data Flow
Raw data was ingested into the "Recruitment/Landing" S3 bucket.
Data was then processed and moved to the "Recruitment/Raw" bucket.
Further processing occurred, and data was stored in the "Recruitment/Trusted" bucket.
Finally, curated data was stored in the "Recruitment/Curated" bucket.
The curated data was then used for analysis, visualization, and creation of data products.
Security and Compliance
The architecture included security measures, such as encryption, access controls, and compliance with data protection regulations, to ensure the safety and confidentiality of HR data.

#### Deliverables
A fully implemented Data Analytics Platform on AWS
Cleaned and transformed datasets ready for analysis
Interactive dashboards for visualizing key recruitment metrics
Documentation of the data wrangling and analysis processes
Recommendations for improving recruitment procedures based on the insights gained
Timeline
The project timeline was 9 weeks.
## Descriptive Analysis Project

### Project Title: Implementing an AWS-Based Data Analytics Platform to Optimize Business License Issuance in Vancouver

#### Objective
The primary goal of this project was to design and implement a Data Analytics Platform (DAP) on AWS for the City of Vancouver, focusing on optimizing the business license issuance process. Through this platform, we aimed to enhance operational efficiency, improve decision-making, and streamline the city's data management capabilities.

![Descriptive Analysis DAP](https://raw.githubusercontent.com/2243038/data-analyst-Simran/main/images/DA.drawio.png)

#### Dataset
The dataset included business license information from the City of Vancouver's Open Data Portal, containing the following key features:
- License Number: Unique identifier for each business license
- Business Name
- Issue Date
- Expiration Date
- Business Category
- Geographic Information

#### Methodology
1. Data Collection and Preparation
2. Data Storage Design
3. Data Ingestion
4. Data Processing and ETL
5. Data Analysis
6. Data Visualization
7. Data Access and Distribution
8. Automation and Orchestration

#### Tools and Technologies
- AWS Services: S3, EC2, Glue, Athena, QuickSight, Glue DataBrew
- Data Analysis: SQL (via Athena), Python (for custom ETL scripts if needed)
- Data Visualization: Amazon QuickSight

#### Deliverables
- Fully functional AWS-based Data Analytics Platform
- Automated ETL pipelines for data processing and preparation
- Interactive QuickSight dashboards presenting key insights on business license issuance
- Detailed reports on Business License Issue Rate and process efficiency
- Recommendations for optimizing the business license issuance process based on data-driven insights

## Data Quality Control Project

### Project Title: Implementation of Data Quality Control Measures in AWS Data Analytic Platform for The City of Vancouver

#### Objective
The primary objective of this project was to establish a comprehensive Data Quality Control (DQC) framework within the AWS Data Analytic Platform for the City of Vancouver. This framework ensures the accuracy, security, consistency, and reliability of data, enhancing the city's ability to make informed decisions and manage resources efficiently.

#### Background
As the City of Vancouver continued to expand its data-driven initiatives, maintaining high data quality was crucial for accurate analytics and decision-making. The AWS Data Analytic Platform project involved processing vast amounts of business license data. However, issues such as data security, governance, and monitoring needed to be addressed to ensure the platform's effectiveness and reliability.

![DA drawio](https://github.com/user-attachments/assets/0542f847-20ec-4859-b3ae-8e4509c8bcbe)


#### Scope
The project focused on the following key areas:
- Data Protection
- Data Governance
- Data Monitoring

#### Methodology
1. Current State Assessment
2. Data Protection (Step 15)
3. Data Governance (Step 16)
4. Data Monitoring (Step 17)
5. Validation Rules and Procedures
6. Training and Best Practices
7. Feedback Mechanism

#### Tools and Technologies
- AWS Key Management Service (KMS) for data encryption
- AWS Glue for metadata management and data cataloging
- Amazon CloudWatch for monitoring data quality metrics and generating alerts
- AWS Trusted Advisor and AWS CloudTrail for security auditing and operational insights

#### Deliverables
- A comprehensive Data Quality Control framework, including data protection, governance, and monitoring processes
- Real-time monitoring dashboards visualizing data quality metrics

#### Timeline
The project was completed in 1 week, covering assessment, implementation, validation, training, and continuous monitoring setup.

This Data Quality Control initiative within the AWS Data Analytic Platform ensured the City of Vancouver's data is secure, well-governed, and reliable, enhancing data-driven decision-making and operational efficiency.
