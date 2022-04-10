# Case-Study
Case Study: How Does a Bike-Share Navigate Speedy Success?

What to know about this project. This is from my google certificate capstone. It allowed me to use R, Excel and data visualization to anser and complete this capstone.
I identified 5 different stages and will highlight them below.  

The Question was How do annual members and casual riders use Cyclistic bikes differently?
- Ask
- Prepare
- Process
- Analyze
- Share
- Act

About the Company: 
Cyclistic, a bike-share company in Chicago. 
The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. 
Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently. 

A bike-share program that features more than 5,800 bicycles and 600 docking stations. 
Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, 
making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. 
The majority of riders opt for traditional bikes; about 8% of riders use the assistive options.
Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day.

Ask:
How do customers who purchase single-ride or full-day passes use bikes differently than customers who purchase annual memberships are Cyclistic members.
What would cause a casual rider to buy an annual membership. Using digital media to influence casual riders to become members.
Are the prices different. Quality of ride different? Product at all different from each user?

Prepare:
My data is located in Excel format. It's organized by ID, Type, Start and End time, Station ID, Start and End Station ID, location and Membership type.
My data source is credible and from 02.2022. Varified from the source.
The data helps identify location, start and end time, day of cycle used, and type of ride.
The problems with the data is some of it's missing. I deleted missing data as I won't be able to give a good estimated guess on the information provided to fill out my data.
I also have enough to continue my analysis.

I’m sorting my data by location to start. Trying to identify any patterns in location.
Is there a location that has low amounts of casual and non casual riders? Is there a preferred time of day and date for these riders?

Process:
Downloaded 12 months of data and organize my data into one spreadsheet
My data is Reliable, Credible, original, current and cited. 
I'm using excel for the first round of cleaning my data. Will check data for errors.
Will use a pivot table for the first step of my analysis.
Will use conditional formatting to highlight days of the week.
 
=IF(O2=1,"SUNDAY",IF(O2=2,"MONDAY",IF(O2=3,"TUESDAY",IF(O2=4,"WEDNESDAY",IF(O2=5,"THURSDAY",IF(O2=6,"FRIDAY",IF(O2=7,"SATURDAY","0")))))))
also Day of the week 1-7 1=Sunday 7=Saturday

Analyze: (Please look at R code)
Calculate the max ride_length
Calculate the mean of ride_length
Calculate the mode of day_of_week
Create a pivot table to quickly calculate and visualize the data. Options:
Calculate the average ride_length for members and casual riders. Try rows = member_casual; Values = Average of ride_length. 
Calculate the average ride_length for users by day_of_week. Try columns = day_of_week; Rows = member_casual; Values = Average of ride_length.
Calculate the number of rides for users by day_of_week by adding Count of trip_id to Values.

Share:

I used a combination of Rmarkdown and excel to visualize my data. I did not use a Tableau for this since a dashboard might not be necessary at this time. 
Notice the peak is on the month of July and slowly goes down on the month of October. Then it takes a big dip on November to January.

The next graph shows how busy it gets throughout the year.
The graph to that the average use of ride share throughout the week.
Casual riders use ride share more on the weekends and the members use the ride share mostly on the weekdays.
Graphs to show the difference of how many riders and the ride duration between the casual and member.

From the data gathered it shows that there are more member than casual riders. 
But the casual riders duration shows that they use the ride share longer.

The peak of how much riders can be found on the Summer Season for both members and casual riders. 
This may be because the riders are visitors and are using the ride share for leisure.
Throughout the week, members use the ride share more on the weekdays. This may be because the members use it for commuting to work.

Act: 
Ideas that can be used The marketing campaign should start advertising on the months of February to May before the busy season.

To entice casual riders to become members, they can give special deals to casual riders.

Sending emails or distributing questionnaires can also get more insights on how to get more casual riders to sign up and gain more data.



