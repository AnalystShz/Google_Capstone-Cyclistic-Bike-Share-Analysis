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


#### *Analyse*


1. Annual Members use the bike-share service consistently throughout the week.
2. The highest number of rides per day for Annual Members is Wednesday. Thursday and Friday are the next two popular days.
3. The lowest figures of rides displayed per day for Annual Members is Sunday.
4. Annual Members cycle on Weekdays than Weekends.
5. The bar chart displays that Casual riders cycle mostly during the weekend as Saturday having the highest figures of rides on a per day basis.
6. Casual Riders cycle less throughout the five week days with Tuesday having the lowest count of rides per day.
7. Cycling is popular amongst Casual riders mostly for fun and leisure.


![Screenshot 2024-03-31 212319](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/7a1df75b-f076-4db8-ac3f-6320c981a201)




1. Annual members cycle most from June to November.
2. The monthly ride count for Annual Members indicates as April being the least popular month and August being the most popular month. 
3. There is a peak in cycle hires in the summer season.
  

## ![Screenshot 2024-03-31 220346](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/9d9d4771-1d9b-4e94-87f2-7b3c4b57a563)


1. Casual riders hire the most bikes from May to November with a significant dip in service usage in the remaining months of the year.
2. The most popular month for Casual riders to hire Cyclistic bikes is August with July and September being the next two most popular months respectively.
## ![Screenshot 2024-03-31 220501](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/4f5ace15-2f46-43fc-8efd-fd7136856154)




- Thirdly, We have analysed the per hour rider count in the busiest months which are July, August and September. Annual Members and Casual Riders Commute most at 5pm. This gives us an indication that the service users prefer this mode of travel especially after work. We can also see that there is a pattern that the bar chart follows between 4pm to 6pm. Here we can come to the conclusion that the riders from both categories commute between 4pm to 6pm.
![Screenshot 2024-03-31 193153](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/b1500598-2068-44ff-b78b-f321f878daff)

![Screenshot 2024-04-01 131754](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/e6cb94d0-cc7a-485c-af0e-e0bd0c9c1138)
![Screenshot 2024-04-01 131641](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/23972051-c826-47d2-9c68-4e8b5721928e)




![Screenshot 2024-03-31 213515](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/fe059ba6-1542-40ff-b19a-4a41b00cca00)


![Screenshot 2024-03-31 213007](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/da9b5416-2764-4091-bb9a-adb5bab60126)
![Screenshot 2024-03-31 213051](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/f14ae1bc-f994-414e-aaeb-bbcd645d2730)

![Screenshot 2024-04-01 124917](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/d14987da-5d7c-4a9b-b27d-957abe56e88c)

![Screenshot 2024-03-31 215921](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/2b4b9f0a-b3d5-4b44-9f90-262059a69c71)

![Screenshot 2024-03-31 215723](https://github.com/AnalystShz/Google_Capstone-Cyclistic-Bike-Share-Analysis/assets/168277622/3b349c11-7445-4ff2-b3a5-e4cd433e1971)


































