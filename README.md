# Bikesharing

#### Overview of the analysis


## Project Overview

This project is a visualization of New York Citi Bike data (August 2019) in order to explore the viability of a bike-sharing business.

### Activity during the month

![preview](https://github.com/Tifarahani/Bikesharing/blob/main/Img/trip_time.png)

- There were over 2.3 million rides for the month of August 2019.
- During the week users are subscribers and during the weekend customer like to use the bike sharing service.
- There is a wide range of the age of the users. Male tend to use the serivce more often than women and the aveerage trip is below 30 minutes.

### Activity during the day

![preview](src/img/week_activity.png)

- Highest activity hours are from 6AM to 8AM and 5:00 PM to 7:00 PM and require the most resources mobilized to manage bikes and client customer.
- During the weekend, the activity seems slower, but steady.

### Activity duration

![preview](src/img/trip_time.png)

- No matter the day or the gender, a bike trip is almost always below 30 minutes and do not go over 45 minutes often.

### Location matter

![preview](src/img/trip_area.png)

- Most ride start locations are in the touristic or business areas on the island of NYC.


### Further analysis:

- Having multiple dataset to see if the service is popular during the winter.
- Aggregation data on promotions to encourage customer for longer trips.===========================================================================
- 

---

#### Deliverable 1: Change Trip Duration to a Datetime Format
In this deliverable the data in the "tripduration" column is converted to a datetime datatype and has the correct time format and DataFrame is exported as a new file without the index column.

![preview](src/img/trip_time.png)

- There were over 2.3 million rides for the month of August 2019.
- During the week users are subscribers and during the weekend customer like to use the bike sharing service.
- There is a wide range of the age of the users. Male tend to use the serivce more often than women and the aveerage trip is below 30 minute
- 
![preview](src/img/week_activity.png)

- Highest activity hours are from 6AM to 8AM and 5:00 PM to 7:00 PM and require the most resources mobilized to manage bikes and client customer.
- During the weekend, the activity seems slower, but steady.

### Activity duration

![preview](src/img/trip_time.png)

- No matter the day or the gender, a bike trip is almost always below 30 minutes and do not go over 45 minutes often.

### Location matter

![preview](src/img/trip_area.png)

- Most ride start locations are in the touristic or business areas on the island of NYC.

#### Deliverable 2: Create Visualizations for the Trip Analysis
Using Tableau, we created visualizations that shows:
- How long bikes are checked out for all riders and genders.
- How many trips are taken by the hour for each day of the week, for all riders and genders.
- A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

- There is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour.
- There is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender.
- A heatmap is created showing the number of bike trips for each hour of each day of the week.
- A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender.
- A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender.

#### Deliverable 3: Create a Story and Report for the Final Presentation

#### Results: Using the visualizations you have in your Tableau Story, describe the results of each visualization underneath the image.

#### Summary: Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.

- The visualisation confirm the popularity of this service in in New York during the month of August 2019.
- The majority of the trips were in Manhattan Island (by male users during morning and evening rush hours).
- We can see this service as a cheaper alternative to the Metro or other public transportation and a way to practive sport.

### Further analysis:

- Having multiple dataset to see if the service is popular during the winter.
- Aggregation data on promotions to encourage customer for longer trips

----
#### Resources:
- Pandas
- Tableau
- Dataset: 201908-citibike-tripdata.csv.zip (https://s3.amazonaws.com/tripdata/index.html)
