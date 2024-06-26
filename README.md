# Cyclistic Bike Share Analysis - A case study by Google Data Analytics 
#### *I am excited to present the culmination of my Google Data Analytics Capstone Project. Through rigorous analysis and the utilization of various data analysis techniques, I have uncovered valuable insights into how customers have been using the Chicago Cylistic Bike Share Service.*




#### Author     : Shezmin Rahim

#### Date       : May 1, 2024

#### Tools      

- Microsoft Excel [Download here](https://microsoft.com)
- Tableau
- Microsoft Word

### Scenario

You are a juinor Data Analyst working on the marketing analyst team at Cyclistic, a bike-share
company in Chicago. The director of marketing believes the company’s future success
depends on maximizing the number of annual memberships. Therefore, your team wants to
understand how casual riders and annual members use Cyclistic bikes differently. From these
insights, your team will design a new marketing strategy to convert casual riders into annual
members. But first, Cyclistic executives must approve your recommendations, so they must be
backed up with compelling data insights and professional data visualizations.

### Characters and teams
 ● Cyclistic: A bike-share program that features more than 5,800 bicycles and 600
docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand
tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities
and riders who can’t use a standard two-wheeled bike. The majority of riders opt for
traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more
likely to ride for leisure, but about 30% use the bikes to commute to work each day.

 ● Lily Moreno: The director of marketing and your manager. Moreno is responsible for
the development of campaigns and initiatives to promote the bike-share program.
These may include email, social media, and other channels.

● Cyclistic marketing analytics team: A team of data analysts who are responsible for
collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy.
You joined this team six months ago and have been busy learning about Cyclistic’s
mission and business goals—as well as how you, as a junior data analyst, can help
Cyclistic achieve them.

● Cyclistic executive team: The notoriously detail-oriented executive team will decide
whether to approve the recommended marketing program.

### About the company
*In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown
to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations
across Chicago. The bikes can be unlocked from one station and returned to any other station
in the system anytime.
Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to
broad consumer segments. One approach that helped make these things possible was the
flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships.
Customers who purchase single-ride or full-day passes are referred to as casual riders.
Customers who purchase annual memberships are Cyclistic members.
Cyclistic’s finance analysts have concluded that annual members are much more profitable
than casual riders. Although the pricing flexibility helps Cyclistic attract more customers,
Moreno believes that maximizing the number of annual members will be key to future growth.
Rather than creating a marketing campaign that targets all-new customers, Moreno believes
there is a solid opportunity to convert casual riders into members. She notes that casual riders
are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.
Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into
annual members. In order to do that, however, the team needs to better understand how
annual members and casual riders differ, why casual riders would buy a membership, and how
digital media could affect their marketing tactics. Moreno and her team are interested in
analyzing the Cyclistic historical bike trip data to identify trends.*

#### *This case study follows the 6 step data analysis process*
1. Ask
2. Prepare
3. Process
4. Analyze
5. Share
6. Act

### *Ask*
Business task - How do annual members and casual riders use Cyclistic bikes differently?

Primary stakeholders : Lily Moreno the director of marketing and the Cyclistic executive team.

Secondary stakeholders : Cyclistic marketing analytics team

### *Prepare*

Data source used : 12 month (2020 January to 2020 December) Cyclistic Trip data from Motivate International Inc: [Click for data source](https://divvy-tripdata.s3.amazonaws.com/index.html) with [license](https://divvybikes.com/data-license-agreement)

Data storage and organization : Each spreadsheet contained trip data for a relevant month/months. There were 13 attributes visible initially such as ;
- ride_id
- rideable_type
- started_at
- ended_at
- start_station_name
- start_station_id
- end_station_name
- end_station_id
- start_lat
- start_lng
- end_lat
- end_lng
- member_casual

Data is ROCCC compliant : The data provided is reliable, Original, comprehensice, current and cited. Data has beeen made available by Motivate International Inc. [View license](https://divvybikes.com/data-license-agreement) 

Are there issues with bias or credibility in this data? There are no issues with the credibility of data however biasing may be caused due to these reasons;

1. There are restrictions to usage of personally identifiable information this means we have no data to identify if the ride was made by a unique rider or a casual rider who makes more than one trip a day or even if it is an annual member utilizing the service as a casual rider for whatever reason.
2. Null values or irrelevant entries such as missing station names or abnormal values in trip data

### *Process*

Data cleaning Processing and manipulation


Micrsoft Excel
- Deleted duplicate, Blanks and Null values
- Insert/delete and renaming of columns
- Formatted relevant fields
- Created a column called ride_length
- Created a column called day_of_week
- Filtered out null and inconsistent values in ride length and deleted rows

Tableau
- Made columns consistent and combined them into a single worksheet.
- Cleaned and transformed data to prepare for analysis


### *Analyse*

In this step, I analyzed the cleaned data to find out how annual members and casual riders use Cyclistic bikes differently.
 
First, I calculated the total number of bikes hired and established how they were shared between casual riders and member riders. Next, I examined how total bike hires were distributed per month, per day and per hour, taking into account the different types of bikes available. This revealed some interesting trends that I shall discuss in the share stage.
 
Next, I examined the count of bike hires between the two types of rider categories compared in a given month of the year and day of the week. The goal at this point was to find out whether casual riders had a preference for certain days or months compared with member riders.

Then, I intended to compare the difference in average ride length between casual riders and member riders. I discovered that casual riders tend to ride for longer periods of time compared to member riders. I was intrigued and decided to explore how the average ride length compares for both rider categories on daily and monthly basis.

Finally I compared how the type of bike hired compared between the two rider categories.


### *Share*


#### 1. Annual Members use the bike-share service consistently throughout the week.
#### 2. The highest number of rides per day for Annual Members is Wednesday. Thursday and Friday are the next two popular days.
#### 3. The lowest figures of rides displayed per day for Annual Members is Sunday.
#### 4. Annual Members cycle on Weekdays than Weekends.
#### 5. The bar chart displays that Casual riders cycle mostly during the weekend as Saturday having the highest figures of rides on a per day basis.
#### 6. Casual Riders cycle less throughout the five week days with Tuesday having the lowest count of rides per day.
#### 7. Cycling is popular amongst Casual riders mostly for fun and leisure.


![Screenshot 2024-03-31 212319](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/7a1df75b-f076-4db8-ac3f-6320c981a201)
***********************************
***********************************



#### 1. Annual members cycle most from June to November.
#### 2. The monthly ride count for Annual Members indicates as April being the least popular month and August being the most popular month. 
#### 3. There is a peak in cycle hires in the summer season.
  

 ![Screenshot 2024-03-31 220346](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/9d9d4771-1d9b-4e94-87f2-7b3c4b57a563)
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

#### 1. Casual riders hire the most bikes from May to November with a significant dip in service usage in the remaining months of the year.
#### 2. The most popular month for Casual riders to hire Cyclistic bikes is August with July and September being the next two most popular months respectively.
 ![Screenshot 2024-03-31 220501](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/4f5ace15-2f46-43fc-8efd-fd7136856154)
***********************************
***********************************

#### 1. Here, we have established that the busiest months for hiring cycles are July, August and September.
#### 2. The ride count for every hour is visualised taking into accounthe 24 hours in a normal day.
#### 3. Annual Members utilize the bike hire service consistently from 6am till 9pm.
#### 4. In demand ride times for Annual Members is between 4pm to 7pm.
#### 5. Whereas Casual riders cycle consistently from 10am to 10pm.
#### 6. Casual Riders maximum bike-hire count is displayed as 6pm in July and 5pm in August and September.
#### 7. Both rider categories prefer using this mode of transportation in the evenings.
 
![Screenshot 2024-03-31 193153](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/b1500598-2068-44ff-b78b-f321f878daff)
***********************************
***********************************
#### 1. This line chart visualises the personal bike type preference of Annual Members.
#### 2. The favourite option is the docked bike however there are riders opting for the other two options available such as electric bike and classic bikes.
![Screenshot 2024-04-01 131754](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/e6cb94d0-cc7a-485c-af0e-e0bd0c9c1138)

///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

#### 1. Docked bikes are the favourite choice of Casual riders. 
#### 2. They hire the most docked bikes at 5pm.
![Screenshot 2024-04-01 131641](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/23972051-c826-47d2-9c68-4e8b5721928e)
***********************************
***********************************

#### 1. Comparing the two rider categories we could establish that there are more Annual Members than Casual Riders.

![Screenshot 2024-03-31 213515](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/fe059ba6-1542-40ff-b19a-4a41b00cca00)
***********************************
***********************************

#### The top 10 commutes trips by Casual riders
![Screenshot 2024-04-01 124917](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/d14987da-5d7c-4a9b-b27d-957abe56e88c)
***********************************
***********************************
#### The most commuted start and end stations by Annual Members and Casual Riders.
![Screenshot 2024-03-31 215921](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/2b4b9f0a-b3d5-4b44-9f90-262059a69c71)

![Screenshot 2024-03-31 215723](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/3b349c11-7445-4ff2-b3a5-e4cd433e1971)

***********************************
***********************************


### *Act*

My key business task was to reveal how Annual Members and Casual Riders used Cyclistic bikes differently. Through my finidings it was established that Annual Members use Cyclistic bikes as a mode to commute to/from work on  a daily basis. They preferred commuting from work on their return home rather than commuting to work in the morning hours. There was a decrease in rides during the weekends in comparison to weekdays however the most popular type of bike all throughout was the docked bike regardless on the day or time. It is also important to note that even if they have purchased annual membership the accumilation of the bike hire service is weather dependant.

When it comes to Casual Riders they did not see Cyclistic bikes as a very popular mode of transportaion on weekdays rather they utilized the service on Saturdays and Sundays. Docked bikes were the most favourite type of the three given options; docked bike, Electric bike and casual bike.

#### Data Analysis Suggestions for Cyclistic Bike Share

- 1. Seasonal Analysis:

Observation: Both Casual riders and Annual Members show an increase in usage during the Summer season.
Recommendation: Further investigate the factors contributing to this seasonal trend, such as weather patterns, tourist influx, or promotional activities during summer months. Tailor marketing efforts or service adjustments to capitalize on increased summer usage.


- 2. Usage Patterns:

Observation: Annual Members predominantly utilize the service on weekdays, while Casual Riders favor weekends.
Recommendation: Develop targeted marketing strategies or incentives to encourage Casual Riders to use the service on weekdays. This could include weekend-specific promotions or packages to attract this demographic during their preferred time frames.


- 3. Membership Preferences:

Observation: There are more Annual Members than Casual riders.
Recommendation: Investigate the reasons behind the disparity in membership numbers. Conduct surveys or interviews to understand the factors influencing individuals' decisions to purchase Annual Memberships versus using the service casually. Consider offering flexible membership options or benefits tailored to different usage patterns and preferences.


- 4. Commuting Behavior:

Observation: Annual Members may be more inclined to purchase memberships based on their interest in commuting to work.
Recommendation: Explore ways to enhance the value proposition of Annual Memberships for commuters, such as integrating additional features or services that cater to their specific needs, such as priority access during peak commuting hours or designated parking areas near workplaces.


- 5. Customer Perception:

Observation: Casual Riders may perceive less importance in purchasing Annual Memberships due to their lower usage frequency.
Recommendation: Conduct market research to better understand Casual Riders' perceptions and preferences regarding membership options. Consider adjusting pricing tiers or introducing pay-as-you-go options to better accommodate their usage patterns and align with their perceived value of the service.


- 6. Long-term Engagement:

Recommendation: Implement retention strategies aimed at both Annual Members and Casual Riders to foster long-term engagement with the bike share service. This could include loyalty programs, personalized recommendations based on usage history, or community events to build a sense of belonging among members.
Conclusion:

By analyzing seasonal trends, usage patterns, and membership preferences, Cyclistic Bike Share can tailor its services and marketing efforts to better meet the diverse needs of both Annual Members and Casual Riders. By understanding the motivations behind membership choices and usage behaviors, the company can optimize its offerings to enhance customer satisfaction and retention.




























