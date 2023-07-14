![](https://github.com/Adeyemi0/Customer-Survey/blob/main/pictures/feedback.jpg)

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

The dashboard image is below or view it [live](https://shorturl.at/djFJ1)
![dashboard!](https://github.com/Adeyemi0/Customer-Survey/blob/main/pictures/survey.png)

## Insight
Based on the banking customer service survey, the following insights can be observed:

1. Demographics:
   Gender: The survey respondents were predominantly male, accounting for 58% of the total, while females represented 42%.
   Age: The majority of respondents fell within the 25-40 age range (57%), followed by 18-24 (23%), 41-56 (16%), and 57 and above (3%).
   Employment status: The largest portion of respondents were unemployed (73%), followed by employed (14%) and self-employed (13%).

2. Security Concerns:
   The respondents' likelihood of having security concerns regarding banking services varied. The highest percentage fell under "Fairly Likely" (34.35%), followed 
   by "Most Likely" (21.37%), "Likely" (17.56%), "Highly Likely" (17.18%), and "Least Likely" (9.54%).

3. Poor Customer Services:
   A significant number of respondents expressed concerns about poor customer services. The highest percentage fell under "Highly Likely" (35.88%), followed by 
   "Most Likely" (30.15%), "Likely" (23.66%), "Fairly Likely" (6.87%), and "Least Likely" (3.44%).

4. Frequent Cash out at ATMs:
   The likelihood of respondents frequently cashing out at ATMs varied, with the majority falling under "Least Likely" (72.14%). The other categories include 
   "Fairly Likely" (14.50%), "Highly Likely" (5.73%), "Likely" (5.73%), and "Most Likely" (1.91%).

5. Delays in transaction completion in branches:
   Respondents' experiences with delays in transaction completion in branches ranged from "Most Likely" (26.72%) to "Least Likely" (10.69%). The other categories 
   were "Likely" (22.90%), "Fairly Likely" (24.81%), and "Highly Likely" (14.89%).

6. Bad Processes:
   The survey revealed that respondents were concerned about bad processes. The highest percentage fell under "Likely" (30.15%), followed by "Highly Likely" 
   (26.34%), "Fairly Likely" (19.47%), "Most Likely" (19.85%), and "Least Likely" (4.20%).

7. Communication Channels:
   Branch visits were most popular among respondents aged 25-40 (60.23%) and least popular among those aged 57 and above (4.55%).
   Email was commonly used by respondents aged 25-40 (60%) and least used by those aged 57 and above (2.50%).
   Internet banking was preferred by respondents aged 25-40 (45.83%) and 41-56 (29.17%) and less preferred by those aged 57 and above (4.17%).
   Mobile apps were popular among respondents aged 25-40 (66.67%) and least used by those aged 18-24 (9.52%).
   Phone calls were utilized by respondents aged 25-40 (50%) and least used by those aged 57 and above (6%).
   Social media was preferred by respondents aged 25-40 (64.52%) and least preferred by those aged 41-56 (6.45%).
   Virtual assistant/chatbot usage was higher among respondents aged 41-56 (50%) and 25-40 (37.50%), and lower among those aged 18-24 (12.50%).

## Recommendations

1. Security Concerns: Addressing the security concerns of customers should be a priority. Banks should invest in robust security measures, educate customers about security practices, and provide clear communication regarding the safety of their services.

2. Poor Customer Services: The high percentage of respondents expressing concerns about poor customer services indicates the need for improvements in this area. Banks should focus on enhancing customer service training for their staff, implementing efficient complaint resolution processes, and actively seeking feedback from customers to identify and address any service gaps.

3. Frequent Cash out at ATMs: The majority of respondents indicated that they were unlikely to frequently cash out at ATMs. Banks could consider analyzing the reasons behind this behavior and evaluate options such as reducing transaction fees, expanding the availability of services beyond ATMs, or promoting alternative channels for cash withdrawals.

4. Delays in transaction completion in branches: The survey highlights the issue of delays in transaction completion at branches. Banks should focus on streamlining their processes, improving staff training, and utilizing technology to reduce wait times and provide faster service to customers.

5. Bad Processes: The dissatisfaction expressed by respondents regarding bad processes suggests the need for process improvements within the banking system. Banks should conduct process audits, identify areas of inefficiency or complexity, and implement changes to streamline processes, enhance transparency, and improve overall customer experience.

6. Communication Channels: Understanding the preferred communication channels of different age groups can help banks tailor their services accordingly. They should invest in digital channels, such as mobile apps and internet banking, which are popular among younger customers. However, it is important to provide a range of options to cater to the preferences of different age groups and ensure all channels are user-friendly and efficient.

7. Overall Customer Retention: To improve customer retention, banks should prioritize addressing security concerns, enhancing customer service, optimizing processes, and providing a seamless and personalized banking experience across multiple communication channels. Regularly monitoring customer feedback, conducting surveys, and taking prompt action on customer suggestions and complaints will contribute to building trust and loyalty among customers.

