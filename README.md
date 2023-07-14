## Introduction
CS Associates is a consulting firm in the Customer Services Industry.
We have carried out a banking customer service survey to better understand customer retention.
Our survey tool has provided us with a basic dashboard on the demography of our respondents. But we are constrained in getting the details and insights we would like to create a comprehensive report.

## Challenges
The issues faced are as follows:
1.	The demography dashboard is not interactive for us to glean insights and create the detailed report we need.
2.	The tool did not provide any meaningful report on the main surveyed opinion (Ranking reasons why customers may want to stop using their bankers).

## Requirement
The company would like your help to surmount the challenges listed above using Microsoft Power BI to enable us easily to share with relevant stakeholders.

## Power BI Concept Applied
1. Power Query: Data Transformation/Cleaning
2. Data Modelling: One to Many

## Data Transformation
The data were transformed with the Power Query editor in Power BI. Some of the steps applied include:
1. Making first rows as headers
2. Added an index column and renamed it ResponseID
3. Created a new query named "Responses" consisting of the ResponseID and Rank possible reasons you may stop using your banker
4. The column "Rank possible reasons you may stop using your banker" was split by the delimiter ","
5. I unpivot the resulting columns from the above step which were renamed "Trigger and Ranking".
6. A conditional column Scale was added using the Ranking column values 1,2,3,4,5 which were renamed Most Likely, Highly Likely, Likely, Fairly Likely, and Least Likely respectively. 
7. The data was loaded into Power BI and a data modeling operation was performed as shown below

![Model!](https://github.com/Adeyemi0/Customer-Survey/blob/main/pictures/cus%20data%20model%20.png)

The dashboard image is below or view it ![live!](https://shorturl.at/djFJ1)
![dashboard!](https://github.com/Adeyemi0/Customer-Survey/blob/main/pictures/survey.png)

