# Bike-Sharing

## Overview
In this project we are analyzing data from a bike sharing business to present to investors and show that this is a solid business proposal.
To solidify the proposal we will use Pandas to change the "tripduration" column from an integer to a datetime datatype and create visualizations of our data. Once we have the correct information, we will:

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.

## Results 

Visualizations were created in Tableau Public: [link to dashboard](https://public.tableau.com/shared/NF2W28MJ2?:display_count=n&:origin=viz_share_link)

- Our first visual analysis was made from data of how long are the bikes used.
We can notice that most of our users rent the bikes for short trips, around 10 min is the most common time of the trip duration.

![Tripduration](https://user-images.githubusercontent.com/78781719/130389900-98463c09-c57e-4764-a685-02914d926ad4.PNG)

- On our second analysis we learned that most of our users are males, being approximately 70% of the users.

![Gender Breakdown](https://user-images.githubusercontent.com/78781719/130390050-b6d5ad3c-3183-4e2d-82a6-6d2dd88b1464.PNG)

- Looking at the gender information, it is important to analyze id there is some information about the duration of the trips between genders, but we conclude that there is no difference between the duration, gender does not affect. 

![Checkout times by gende](https://user-images.githubusercontent.com/78781719/130390234-1eaa0127-613b-41f5-a5ae-cf9aca6e1fc1.PNG)

- It is also important to analyze when are the bikes most rented, by time and day of the week.
We found that bikes are used mostly from 7am-8am and 5pm-6pm, being Thursday the day of more rents, and Wednesday the least rents.
On Saturdays we can appreciate a constant use between 10 am and 6 pm. 
They are almost not used at night until ~6am, we could schedule  maintenance during these hours.

![Trips by weekend](https://user-images.githubusercontent.com/78781719/130390557-d4d86088-123d-4d1f-b066-21c8747e303a.PNG)


- If we analyze the trips by week and by gender, the pattern of use is the same but, since there are more males using the bike service, we can see it as a darker color.

![trips by gender](https://user-images.githubusercontent.com/78781719/130390958-7d487e0a-3f87-4a81-aa13-6550ce16e45a.PNG)

- We wanted to check who are most likely to become subscribers of our bike service, and we can see how males are the majority of subscribers.

![USer](https://user-images.githubusercontent.com/78781719/130391132-3eaf943b-8fa0-4a03-8102-e858bb652c15.PNG)

- To know where is more convinient to locate our bike stations, we made an analysis of the places where people start their trips. People that come from New Jersey, people on Times Square or Empire State Building are the ones that need the service, so it is convinient to locate more bikes around these areas. 

![Starting locations](https://user-images.githubusercontent.com/78781719/130391288-533bd81c-ef9d-49ac-a687-f8dfa3432fb7.PNG)

