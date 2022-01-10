# Bikesharing

The objective is to convince investors that a bike-sharing program in Des Moines is a good business proposal. For the proposal, to be approved we are putting together a bike trip analysis. This will give us a good insight various ways.

For this analysis, we used Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, create a set of visualizations.

- Show the checkout time for Users and by Gender
- Show the trips by weekday and by gender
- Show the user trips by gender by week 
- Show the bike volume rented by weekday
- show the bikes rented for top 10 stations
- show the start time by station and bike ID

## Environment

- Python  
- Tableau Public    

## Deliverables

- Deliverable 1: Change Trip Duration to a Datetime Format using Pandas
- Deliverable 2: Create Visualizations for the Trip Analysis in Tableau
- Deliverable 3: Create a Story and Report for the Final Presentation published to Tableau Public

## Results

## Deliverable 1


- See NYC_Citibike_Challenbge.ipynb python pandas transformation of the tripduration to datetime using
citibike_tripdata["tripduration"] = pd.to_datetime(citibike_tripdata["tripduration"], unit='s')

![image](https://user-images.githubusercontent.com/90879122/148725742-68a0da2c-1d90-4ebf-86e1-96f36b9abca4.png)

## Deliverable 2

### There is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour

![image](https://user-images.githubusercontent.com/90879122/148726076-9480d9ff-47f8-46c3-831c-e411e0bfc9c1.png)

### There is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender
![image](https://user-images.githubusercontent.com/90879122/148726122-5fe90811-35e9-4e6f-8066-46449c64825a.png)

### A heatmap is created showing the number of bike trips for each hour of each day of the week
![image](https://user-images.githubusercontent.com/90879122/148726172-14487c2c-fcfd-4b2a-85bc-32fa7293513c.png)

### A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender
![image](https://user-images.githubusercontent.com/90879122/148726203-79a16b37-6fca-4ed3-81b3-f5b158f79373.png)

### A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender
![image](https://user-images.githubusercontent.com/90879122/148726225-249feef3-c33b-490c-809c-0bd0c9201d8b.png)

## Results
## Deliverable 3

### Bike volume rented by weekday for top10 stations
https://public.tableau.com/app/profile/indira8561/viz/Bike0/Bikevolumerentedbyweekdayfortop10stations

![image](https://user-images.githubusercontent.com/90879122/148726778-e6fcb95e-9ed4-40e3-be16-b21ed3bb7079.png)

### Bikes rented for top 10 stations
https://public.tableau.com/app/profile/indira8561/viz/Bike01/Bikesrentedfortop10stations
![image](https://user-images.githubusercontent.com/90879122/148726813-adf9610c-c41a-4479-93cc-d227bd26c64b.png)


### Start time by station and Bike ID
https://public.tableau.com/app/profile/indira8561/viz/Bike02/StarttimebystationandBikeID?publish=yes
![image](https://user-images.githubusercontent.com/90879122/148726850-67470b7a-7e19-42ba-bd05-d1008228cbfb.png)

#citibike Story

# Summary Final overview

This analysis did help the business proposal  to gain more insights.
https://public.tableau.com/app/profile/indira8561/viz/Bike1_16417664414260/Story2?publish=yes

![image](https://user-images.githubusercontent.com/90879122/148726974-64f380fb-780c-4b2d-a723-0e968dd4af55.png)

