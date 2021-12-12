# BootCamp-Mod-14-Bikesharing

Performing analysis on CitiBike NYC data to provide visualizations using Tableau.

## Overview of Project

### Purpose
The purpose of this analysis is to use CitiBike data from New York City (NYC) in Tableau to create visualizations for a pitch to an investor in hopes of getting them to invest in the idea of creating a similar bike share program in Des Moines, Iowa.

## Visualizations
[link to Tableau Story](https://public.tableau.com/app/profile/michelle.outlaw/viz/Module14CitiBikeChallenge/NYCCitiBikeData?publish=yes)
### Module Visualizations
#### Page 1: Demographics
<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-14-Bikesharing/blob/main/Images/Tableau_Page_1.png" width="140.5" height="275.5"/></p>

- To begin the Tableau story, it is good to get the demographics of our data.
  * The data contains 2,344,224 trips taken in the month of August, 2019.
  * More than the 75% of the user were subscribers.
  * Over 65% of the users were men.

#### Page 2: Top Starting and Stopping Locations
<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-14-Bikesharing/blob/main/Images/Tableau_Page_2.png" width="489" height="300.5"/></p>

- The top starting locations map almost identically matches the top ending locations map in both the size, color, and location of the dots.
- The likely conclusion for this is that the bikes make a round trip and end in their starting position.

#### Page 3: August Peak Hours
<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-14-Bikesharing/blob/main/Images/Tableau_Page_3.png" width="481.5" height="281.5"/></p>

- Over the course of August, the most trips were taken during the hours of 5 pm and 7pm, with a third peak of 8 am to 9 am.
- Therefore, the peaks seem to occur during morning and evening rush hour times, leading to the conclusion that the majority of the rides were taken by people traveling to and from work.

### Challenge Visualizations
#### Page 4: Checkout Times by Users
<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-14-Bikesharing/blob/main/Images/Tableau_Page_4.png" width="495.5" height="305.5"/></p>

- Most of the trips were 5 minutes long.
- With the previous conclusions, this shows that most people who used the bikes lived close to their jobs.

#### Page 5: Checkout Times by Gender
<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-14-Bikesharing/blob/main/Images/Tableau_Page_5.png" width="494" height="304"/></p>

- When broken down by gender, most males took 5-minute trips, most women took 6-minute trips, and unknown users mostly took trips between 10 and 25 minutes.
- It can be concluded that those marked with a gender are subscribers and those marked as unknown must be customers.
- Further enforcing the idea that the subscribers are those that live in NYC and customers are visitors to NYC.        

#### Page 6: Trips by Weekday per Hour
<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-14-Bikesharing/blob/main/Images/Tableau_Page_6.png" width="494.5" height="271"/></p>

- The heatmap is darkest during the hours of 8 am to 9 am Thursdays and 5 pm to 7pm Mondays and Thursdays.
- Confirming that most trips are taken on weekdays during rush hours.

#### Page 7: Trips by Gender (Weekday per Hour)
<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-14-Bikesharing/blob/main/Images/Tableau_Page_7.png" width="505.5" height="298"/></p>

- Both males and female heat maps confirm the previous heat map that most trips are taken on weekdays during rush hours.
- However, for unknown users, trips were mostly taken between 11 am and 6 pm on the weekends.
- This is another confirmation that those marked male or female must live in NYC and those marked as unknown must be visiting NYC.

#### Page 8: User Trips by Gender by Weekday
<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-14-Bikesharing/blob/main/Images/Tableau_Page_8.png" width="495.5" height="172.5"/></p>

- Most customers are marked as unknown and show more trips on the Saturday and Sunday.
- Subscribers are mostly male, some female, and use bikes most during the work week.
- A final confirmation that those marked male or female must live in NYC since they are subscribers and those marked as unknown must be visiting NYC because they are customers.


## Summary
### Conclusions 
- Based on the data from NYC, most of the users are subscribers.
- Most subscribers take trips during rush hours on Monday through Friday, showing that subscribers live in NYC.
- Most customers take trips between 11 am and 6 pm on Saturday and Sunday, showing that customers are visitors of NYC.
- All of this shows that this would be a worthwhile service in Des Moines, Iowa because residents that work near downtown can use them to commute to work like in NYC, or they can use the bikes to travel to and from lunch during work days or weekend events.

### Additional Visualizations
- While it looks like most bikes start and stop in the same location, it would be good to confirm this. 
  * A good visualization to do this is to have a graph of the count on the y-axis and the distance between the starting and stopping locations.
  * Another way to confirm that the bikes start and stop in the same location would be to compare the start station ID with the end station ID and chart how many match.


