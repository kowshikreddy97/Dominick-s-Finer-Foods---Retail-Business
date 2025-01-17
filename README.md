Introduction: 
-
Dominick’s Finer Foods (DFF) founded in 1918 by a Sicilian immigrant Dominick DiMatteo was a major grocery store chain in the Chicago area. The company evolved from a small deli to become Chicago’s second-largest supermarket chain. Over the decades, DFF expanded significantly and they underwent several changes in ownership which impacted DFF’s performance.

The primary objective of this project is to design and implement a data warehouse for DFF using the store-level data collected from 1989-1994. This involves integrating the data from various sources ensuring data consistency to provide a consolidated view of the company’s operations. The data warehouse will facilitate historical data analysis to understand the patterns in customer behavior, sales trends, and marketing strategies. This information is essential to understand the factors that contributed to DFF’s success and downfall.

Business Questions:
-
  1. Which store has the highest store traffic for the last quarter of 1994?
  2. Which holiday week in 1991 and 1992 saw the highest grocery sales in the low-tier Buffalo Grove stores?
  3. How does the profit margin of toothpaste vary by brand?
  4. What are the monthly average sales amounts for the BAKERY, DAIRY, PHARMACY, COSMETIC, and HABA departments across Dominick's Fine Food stores located in Naperville and Schaumburg during the year 1994, and how do these averages compare among the different departments within these locations?
  5. What were the highest sales contributions from single and retired individuals in the Buffalo Grove stores for BUDWEISER BEER N.R.B during the Thanksgiving week of 1993?

To know more about the insights uncovered for these business questions, please check out my project report :)

Tools and Technologies:
-
- SQL Server 2016
- Visual Studio
- SSMS: SQL Server Management Studio - To create and maintain data warehouse and data marts.
- SSIS: SQL Server Integration Services - To build ETL pipelines and perform ETL processes.
- SSAS: SQL Server Analysis Services - To create hyper dimensional cubes to analyze the data efficiently.
- Power BI
- Tableau
- Report Builder

Features:
-
- Followed Kimball methodology and utilized dimensional modeling technique while implementing the project.
- Created a temporary staging area using SSMS.
- Created Data marts to store data in fact and dimensional tables.
- Implemented an ETL pipeline and loaded data into staging area by extracting DFF's data from various sources such as Excel files and other databases.
- Performed transformations in staging area and loaded data into data marts.
- Utilized BI tools to create reports and dashboards for business queries and delivered valuable insights to stakeholders.
