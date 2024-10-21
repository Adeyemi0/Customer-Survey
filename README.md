![](https://github.com/Adeyemi0/Customer-Survey/blob/main/pictures/feedback.jpg)

## Table of Contents

1. [Introduction](#introduction)
2. [Challenges](#challenges)
3. [Requirement](#requirement)
4. [Power BI Concept Applied](#power-bi-concept-applied)
   - [1. Power Query: Data Transformation/Cleaning](#power-query-data-transformationcleaning)
   - [2. Data Modelling: One to Many](#data-modelling-one-to-many)
5. [Data Transformation](#data-transformation)
   - [Steps Applied](#steps-applied)
6. [Data Model](#data-model)
7. [Dashboard](#dashboard)
   - [View Live Dashboard](#view-live-dashboard)
8. [Insight](#insight)
   - [1. Demographics](#1-demographics)
   - [2. Security Concerns](#2-security-concerns)
   - [3. Poor Customer Service](#3-poor-customer-service)
   - [4. ATM Cash-Outs](#4-atm-cash-outs)
   - [5. Transaction Delays in Branches](#5-transaction-delays-in-branches)
   - [6. Concerns Over Bad Processes](#6-concerns-over-bad-processes)
   - [7. Communication Channels](#7-communication-channels)
10. [Recommendations](#recommendations)
   - [Product Development](#product-development)
   - [Customer Support](#customer-support)
   - [Digital Adoption](#digital-adoption)
   - [Operational Efficiency](#operational-efficiency)
   - [Security Messaging](#security-messaging)


## Introduction
CS Associates is a consulting firm in the Customer Services Industry.
They have carried out a banking customer service survey to better understand customer retention.
Their survey tool has provided us with a basic dashboard on the demography of their respondents. But they are constrained in getting the details and insights they would like to create a comprehensive report.

## Challenges
The issues faced are as follows:
1.	The demography dashboard is not interactive for the company to glean insights hence the need to create the detailed report.
2.	The tool did not provide any meaningful report on the main surveyed opinion (Ranking reasons why customers may want to stop using their banks).

## Requirement
The company needs help to surmount the challenges listed above using Microsoft Power BI to enable us easily to share with relevant stakeholders.

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

The dashboard image is below and you calso view it live [here](https://app.powerbi.com/view?r=eyJrIjoiMDhiMDhmNTEtODk3NS00NWY5LWJhNzgtYmNiMTdiYzg5YmQ3IiwidCI6IjQyOWYxMWVhLWM3NmQtNDczMS05M2M5LWM0MDZiNGYzMmE1YSJ9)
![dashboard!](https://github.com/Adeyemi0/Customer-Survey/blob/main/pictures/survey.png)

## Insight

### 1. Demographics:
The survey's demographic profile suggests the bank's services appeal predominantly to males and individuals aged 25-40, the prime age group for financial services. A notable insight is that 73% of respondents are unemployed, indicating potential opportunities for financial products aimed at the unemployed or non-traditional income earners. Tailoring offerings like savings plans, lower-fee accounts, or financial literacy programs to this demographic could improve engagement.

### 2. Security Concerns:
A high percentage of respondents (34.35%) are "Fairly Likely" to have security concerns, while 56.11% range from "Likely" to "Most Likely." This reflects a need for improved communication and transparency about the bank’s security measures. Addressing these concerns through stronger messaging about cybersecurity could enhance trust and retention.

### 3. Poor Customer Service:
Concerns around poor customer service are prominent, with 35.88% reporting it as "Highly Likely." The bank should prioritize enhancing customer support, possibly by improving response times, employee training, or adopting a more robust customer service infrastructure such as AI-driven support systems to mitigate dissatisfaction.

### 4. ATM Cash-Outs:
A significant 72.14% are "Least Likely" to frequently use ATMs, suggesting a shift towards cashless transactions or digital banking methods. This could indicate an opportunity to expand digital wallet services or incentivize online and mobile banking usage, which align with customer preferences.

### 5. Transaction Delays in Branches:
With 26.72% of respondents citing transaction delays as "Most Likely," inefficiencies in branch operations seem to be a pain point. Streamlining in-branch processes, introducing appointment scheduling systems, or digital alternatives could reduce wait times and enhance customer experience.

### 6. Concerns Over Bad Processes:
The majority (30.15%) are concerned about inefficient banking processes. An opportunity exists for the bank to focus on process reengineering to streamline customer journeys, making banking simpler and more intuitive, which could directly reduce customer frustration and improve satisfaction.

### 7. Communication Channels:
Branch visits, email, internet banking, and mobile apps are heavily used by the 25-40 age group. However, the 57+ age group shows minimal use across all digital channels, highlighting a digital divide. This suggests potential value in targeted campaigns for older customers, promoting digital literacy and usage of internet banking or mobile apps. Additionally, improving virtual assistant/chatbot services for the 41-56 age group could enhance their interaction with the bank's services.

### Recommendations:
- **Product Development**: Develop financial products for the unemployed demographic (e.g., no-fee accounts, micro-loans).
- **Customer Support**: Implement AI-driven customer support solutions to address customer service concerns.
- **Digital Adoption**: Promote cashless solutions and improve the digital banking experience, especially for older customers.
- **Operational Efficiency**: Streamline branch processes to reduce transaction delays.
- **Security Messaging**: Enhance communication regarding banking security to reduce customer concerns.
