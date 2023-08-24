## Introduction
In today's fast-paced digital competitive world, staying ahead of the curve is not just an advantage for business, it's a necessity. Marketing analysis is one of the most effective ways to edge out competition. A comprehensive marketing analysis serves as a strategic linchpin, offering an expansive view of a company's position in the market and its potential for growth. By peering into the depths of data, businesses can uncover hidden gems of knowledge that inform key decisions, drive resource allocation, and illuminate pathways for innovation. 
When meticulously executed, marketing analysis has unimaginable transformative powers. Examples of such power is the remarkable ability to predict trends before they emerge, identifying untapped marketing segments and tailoring campaigns and strategies to fit this market. 
Just like a compass that guides a ship, a data analyst is the steady hands at the helm of a company’s data-driven decisions voyage and in the heart of every comprehensive marketing analysis lies a data analyst with the ability to decipher the intricate messages embedded within the data. 
Overview of the dataset
This dataset belongs to a fictious company named Maven Marketing Company. The data contains a table with 2,240 records and 27 columns which covers information about five different campaigns carried out by the company in order to improve its sales. The original dataset can be found here. 
Objective of the project 
The goal of this comprehensive marketing analysis is to unravel the hidden insights within the company’s data by uncovering consumer behavior pattern, assess the campaigns effectiveness thereby optimizing marketing strategies, and ultimately enabling Maven to make well-informed data-driven decisions
Data Analysis Process
In data analysis, there are set of processes whose significance cannot be overstated and which are to be followed meticulously in order to ensure that the data is accurately processed and the result of such analysis is reliable and useful. Here are the steps I took in order to analyze this dataset: 
1.	Business Question
2.	Data Gathering 
3.	Data Exploration and Cleaning 
4.	Data Analysis
5.	Data Visualization 
6.	Insights and Recommendations 
## Business Question 
Data analytics process generally begins with defining a specific, measurable, action-oriented and relevant business questions that the analysis aims to address. The business questions serve as a guide for the entire analysis, helping to focus efforts and determine the scope of the data gathering and analysis. The following business questions are what I intend to answer by analyzing this dataset:
1.	Assess the Campaign Effectiveness: By examining the data on campaign successes and failure, we can determine which of the marketing campaign have the best ROI and was most in driving sales which will help the company in making important decisions about resource allocation.
2.	Which of the products generated the highest profit, and which one generated the lowest?
3.	Does the overall income of an household have an effect on the purchasing power of the family?
4.	Does the customers' educational level have an impact on the medium of purchase
5.	What Are Customer Preferences and Trends: Identifying patterns in consumer behavior, preferences, and engagement. Understanding how customers interact with the company’s products can provide valuable insights into tailoring marketing strategies to meet their needs.
6.	Refine Target Audience Segmentation: By analyzing customers demographic data and profiles, we can gain insights in to which demographics respond best to campaigns or whether certain age groups, genders, or geographic regions respond more favorably to marketing campaigns. These insights can inform decisions on targeted messaging or content for each of the customers’ specific group.
7.	Any other data-driven insights into the sales data. 
## Data Gathering 
	The dataset was provided online as part of the Data Analytics challenge from a fictitious Maven Marketing Company. Thereafter, the dataset was loaded into Excel for analysis. 
## Data Exploration and Cleaning 
Data exploration is a crucial data analysis procedure that involves delving into the dataset to gain a deeper understanding of its structure, contents, patterns, and potential relationships. It is an essential step that helps analysts identify trends, anomalies, and insights that may not be immediately apparent. Data exploration lays the foundation for subsequent analysis by providing context and guiding the formulation of hypotheses and strategies. While Data Cleaning 
Upon getting the dataset, I explored to ensure that this dataset is relevant and align with the business question After inspecting the dataset, it was discovered that this dataset has many qualities issues including duplicate values, missing values, outliers. The following steps were taken to ensure data quality and integrity:
1.	Removing duplicate values and blank cells
2.	In the Education column, “Graduation” was replaced with “graduate”
3.	Checked for inconsistent column formatting and data types and each column was properly formatted in to the correct data type. 
4.	The products price columns which were formatted as “text” was changed into the “currency” format. 
## Data Analysis 
1.	I created a new column named the “Age Category” which grouped the age column into categories three age range – Young Adult, Middle Age and Old 
2.	I created a new column named Age which I calculated from the ‘Birth’ column in order to delve in to the different age bracket that the customers fall in to, which will be useful in analyzing customer demographic data. 
3.	Also, part of my analysis process was to create pivot tables. Pivot tables are useful for summarizing and aggregating because they allow you to quickly analyze and visualize patterns, trends, and relationships within your data.
## Data Visualization 
For visualization, I created a dashboard in Excel in order to better display my findings and communicate my analysis using visuals. 
## Insights 
Leveraging the comprehensive market analysis of the Maven Marketing company dataset, I acquired valuable insights and effectively addressed inquiries that played a pivotal role in shaping strategic decisions and optimizing business outcomes.
The Channel Performance Comparison was an analysis made between the three channels used by Maven Marketing for sales and they are Web, Catalogue and Store. In the course of my analysis, I discovered that the store performance was the most successful channels contributing a significant of 46% of total sales. In contrast to the Web and Catalogue channels which had 33% and 21% respectively. This insight underscores the importance of the store channel and its impact on the company’s sales dynamics and further questions like “does the age or educational level of customers have effect on the medium of purchase” can revealed the reasons for the attributed success and failure of each channel. 

![Channel Performance ](https://github.com/mansuurah/Excel_marketing_analysis/assets/136700743/d65f2811-15f2-45c4-bb2b-f43e21aa3bab)

# Which products are best performing?

Analyzing the sales data of Maven Marketing company revealed that Wine and Meat products hold the distinction of being the top-performing items of the total sales revenue. The wine product generated an impressive revenue exceeding $680k which represent 50.24% of the total sales revenue while Meat generated about $374k. 
The underlying reasons behind the success of these specific products warrant a comprehensive investigation. It becomes evident that a nuanced understanding of customer demographics and behavioral trends is integral to deciphering the driving forces behind these exceptional sales figures. By delving into customer preferences, purchasing habits, and potentially conducting segmentation analysis, deeper insights can be gleaned to ascertain the factors contributing to the elevated performance of Wine and Meat products. 

![Top product sales](https://github.com/mansuurah/Excel_marketing_analysis/assets/136700743/98e19044-8686-455d-9224-5e46408cab0c)

Which of the marketing campaign was the most successful according to customers response? 
Campaign 4 was the top-performing campaign in terms of customer response which generated 167 customers with campaign 5 and 3 closely behind each generating 163. The reason for the success of campaign 4 can be better understood by assessing the strategy, materials, content, resources used in this campaign. 

![Campaign Performance](https://github.com/mansuurah/Excel_marketing_analysis/assets/136700743/7692e22d-c14b-4e9f-869e-38a0896a601b)

Geographical distribution of Income and Sales
From the analysis of the geographical distribution of both customer income and sales data, a pertinent insight emerges. The examination of customer income across regions highlights Spain as the highest income-generating locale, contributing a substantial sum of $56,360,083.00. Remarkably, a correlational analysis of sales data from the same region indicates that customers based in Spain exhibit the highest web purchase activity, totaling $4,382. This confluence of high-income generation and significant web-based purchasing underscores the pivotal role that the Spanish market plays in driving revenue and engagement for the company.

![Geographical analysis](https://github.com/mansuurah/Excel_marketing_analysis/assets/136700743/54f29383-1caa-42b4-b29f-ef24b0d1468c)

Upon meticulous analysis, I discovered that the quintessential customer archetype is characterized by being a graduate, married, and boasting an average annual income of $52,247. This insight encapsulates a valuable snapshot of the company's target demographic, shedding light on key attributes that can significantly inform marketing strategies and customer engagement initiatives.

![Customer profile](https://github.com/mansuurah/Excel_marketing_analysis/assets/136700743/fbddb07e-859d-46db-8074-795c0f3ec9fa)

## Recommendations
1.	Maven Marketing should investigate factors such as events, contents, promotions and other external factors that may have influenced customers’ behavior that contributed to the success of campaign 4 while also conducting a cross-comparison of Campaign 4’s attribute with others to unearth key differentiators and these successful elements can be replicated and incorporated into future campaigns and enhance customer engagement
2.	Leverage the unique preferences of each country’s market to curate a product assortment that resonates with local tastes and trends. Conduct market research to identify popular products that align with the interests of high-income consumers. Offering exclusive or specialized items tailored to the audience can further drive sales and elevate the company's revenue streams.


