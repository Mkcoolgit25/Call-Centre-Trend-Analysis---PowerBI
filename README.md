<h1 align="center">Call Centre Trend Analysis</h1>

### Overview
For this project, I'll play the role of Digital Accelerator hired by a Manager of a Call Centre to identify trends &amp; get transparent Insights from the data of the Call Centre. I've been tasked with sharing a report visualizing the data in clear &amp; precise manner that focuses on accurate overview of long-term trends in customer &amp; agent's behavior.
<br><br>
### Business Requirements:-
Present a Visualizing report in Power BI reflecting all the relevant Key Performing Indicators(KPIs) & metrics from the dataset of which some of the mentioned metrics by the stakeholders are :-
* Overall Customer Satisfaction
* Overall Calls Answered/ Calls Abandoned
* Calls by Time Duration
* Average Speed of Calls Answered
* Agent's Performance - Talk Duration VS Calls Answered
<br><br>
### Methodology:-
The dataset for the Call Centre Trend was received in csv format & the analysis & visualization was done using Microsoft Power BI.

The dataset was loaded into Power BI & Data Transformation step was done as it was already a cleaned dataset.

* Firstly, I've replaced the null values with 0 in 'Speed of Answer in Seconds', 'Average Satisfaction Rating' columns & in 'Average Talk Duration' column replaced the null value with 00:00:00 in Time format.
* Next, I've replaced the Y with YES & N with NO in Answered(Y/N) & Resolved columns
* For the next step, I've added a conditional column named 'Customer Satisfaction' where the values were dependent on the 'Customer's Rating' column
* Lastly, I've created a Measures Table which include DAX measures such as 'Average Rating by Customers', 'Average Speed of Calls Answered', 'Calls Answered', 'Calls Abandoned', ' Positive Satisfaction Rating', 'Neutral Satisfaction Rating', 'Negative Satisfaction', 'Overall Satisfaction Rating', 'Resolved Calls', 'Unresolved Calls' & 'Total Calls' measures
<br>
Upon completion of the Data Transformation, I proceeded with Data Visualizations as tasked by the stakeholders.

There are 3 Slicers for this report which are Filter by Topic, Agents & Months along with a Clear All Slicer button.
<br><br>

### INSIGHTS:-
The Key Performing Indicators(KPIs) for the Call Centre Trends are :- Total Calls - 5000, Calls Answered - 4054, Calls Abandoned - 946, Agents - 8, Overall Customer Satisfaction - 49.90%. The KPIs for the Agent's Performance Analysis are :- Positive Ratings -2023, Negative Ratings - 813, Topics - 5 & Calls Resolved - 3646. The Key Performance Indicator metrics is visualized by using CARD Visual.
<br><br>

Visuals in Call Centre Trend Analysis:-<br>
* A Pie chart visual is used to visualize the number of calls & percentage of calls done Topic wise. Most calls, 1022 calls are regarding Streaming issues with Contact related calls being the least i.e. 976
* A Gauge chart visual to identify the Average of Customer's Rating. The Average Customer's Rating is 2.76 falling quite short of the target 4.10
* A Stacked column chart visual to find the numbers of call made Month wise. Months of January had the most calls - 1772, February had 1616 & March had 1612 calls
* A Donut chart visual indicating the number of calls where Customer's issue was Resolved or remained unresolved. The number of Resolved calls were 3646 (89.94%) & Unresolved calls 408 (10.06%)
* A Clustered column chart visual that indicates the number of calls by the Customer's Satisfaction. Most of the Rating was Neutral(1218) followed by Satisfied(1180), Not Served(946), Very Satisfied(843), Extremely dissatisfied(417) & Dissatisfied(396) ratings respectively
* Another Gauge chart visual indicating the Average speed of Calls Answered which is 54.75 seconds
<br><br>

Visuals in Agent's Performance Analysis:-<br>
* A Clustered column chart visual showcasing the number of Calls Answered, Calls Resolved & Calls Unresolved by the different Agents. Agent Jim made the most number of calls(536) & also most number of issues resolved on calls(485). Agent Becky has most number of calls unresolved(55). Agent Stewart made the least number of calls(477) & also has the least number of calls resolved(424) while Agent Greg had the least number of calls Unresolved(47)
* A Funnel Chart visual that indicates Overall Customer Satisfaction(in percent) by the respective Agents. Martha has the highest Overall Customer Satisfaction (52.72%) followed by Stewart(51.36%), Becky(50.48%), Jim(50%), Dan(49.90%), Diane(49.10%), Greg(48.01%) & Joe(47.52%)
* A Drill Through Area chart visual that shows the number of calls answered, calls resolved & calls unresolved by the number of Days & Months. 11th of January had the most calls answered(68) & most calls resolved(63) while 30th of March had least number of calls answered(16) & resolved calls(14)
* A Stacked column chart visual that shows the average speed of calls answered for different Agents. Agent Diane had the least average speed of call answered of 52.45 seconds while Agent Joe had the highest average average speed of call answered at 57.94 seconds
* A Table visual that indicates the overall Agent's performance on different metrics such as Total Calls made, Calls Answered, Calls Abandoned, Calls Resolved, Calls Unresolved, Number of Positive, Neutral & Negative Ratings & the Overall Customer's Satisfaction Rating for each of Agents.
<br><br>

### Conclusion:-
The Call Centre Trend Analysis Report provides an in-depth analysis & INSIGHTS of the data of the Call Centre that enables the Manager of the Call Centre & other stakeholders to understand the Agent's & Customer's behavior & make necessary data driven decisions to improve their operations & come-up with better strategy.
