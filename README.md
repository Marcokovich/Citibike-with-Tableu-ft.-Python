# Citibike-with-Tableu-ft.-Python
Link to Dashboard (https://public.tableau.com/app/profile/marcos.galarza/viz/CitiBike_16488582974950/Story1#1)
## 1. Project Overview
### Background:
We are given a csv file with the data for a bike sharing venture in New York. We are to make an analysis for one of the key stakeholders to solidify a deal in Des Moines to make a similar venture. We are to format a column from the csv file before making the visualizations in Tableau.
### Purpose:
The Python Code Provided will format the proper .csv file to be placed in the Resources folder. It will use the Datetime() function to format the tripduration column to be measured in seconds. Then that csv file is loaded into Tableau to create the 7 visualizations. Finally a final analysis will wrap up the project to explain the visualization of the data in a pitch to the stakeholder.
## 2. Results:
### Table 1: Checkout Times for Users:

![image](https://user-images.githubusercontent.com/71575748/161404097-34d5bc24-a75a-4edb-8d28-1b89cbdc61ae.png)

- Peak usage duration is around 5 minutes and steeply declines until 20 minutes and hovers close to 0 users at 50 minutes.

### Table 2: Checout Times for Users Divided by Gender:

![image](https://user-images.githubusercontent.com/71575748/161404119-37bff8f1-447c-4cc4-994d-bf52e7233e49.png)

- Male and Female follow the same trend as table 1. Both peak at 5 minutes and steeply decline until 20 minutes and hover close to 0 at 50 minutes
- Unknown has a different shape and plateaus rather than peaking and begins to decline steeply at 30 minutes and hovers close to 0 at 40 minutes.

### Table 3: Heatmap Based on Hours and Weekday:

![image](https://user-images.githubusercontent.com/71575748/161404130-ea0469cd-5e09-4239-a84e-2dfd0083f8c1.png)

- Starttimes peak at 8 AM on weekdays
- On Mondays, Tuesdat, Thurdays, and Fridays they peak again at 5 PM and 6 PM
- Saturdays and Sundays peak around 3 PM

### Table 4: Heatmap Based on Hours and Weekday Breakdown with Gender:

![image](https://user-images.githubusercontent.com/71575748/161404148-a41b6148-36ac-46fe-bc5a-4b099a0ce18a.png)

- Although less dense, Follows the same trends as table 3

![image](https://user-images.githubusercontent.com/71575748/161404155-3374dbf9-e2a1-4d6f-bfd5-367f279ca300.png)

- Identical to table 3, moreso than table 4-a

![image](https://user-images.githubusercontent.com/71575748/161404162-7bd134fd-ab9f-403c-ac22-d093e03f8f41.png)

- Only has the weekend trends, rather cold during weekdays

### Table 5: Types of Users for Each Weekday Divided by Gender:

![image](https://user-images.githubusercontent.com/71575748/161404336-9fd6087c-a571-420b-b3bb-1dc1d13036ee.png)

- Male Subscribers have the highest number of users.
- Thurdays are popular for subscribers, this makes sense given previous graph results.
- Subscribers with Unknown gender are sparse, makes sense as a result of info shared.
- Weekends are popular among Customers.

### Table 6: Starting Station Bubble Map:

![image](https://user-images.githubusercontent.com/71575748/161404375-cfa905c3-779b-4577-8a37-f9a2a202eed5.png)

- The most used Station is one located near West Manhattan.
- Manhattan is the most populous tourist area, likely due to tourism.
- Usage drops off in the outskirts.

### Table 7: Terminating Station Bubble Map:

![image](https://user-images.githubusercontent.com/71575748/161404362-b7d52632-b50f-404e-80c3-9e43a92a0c92.png)

- The same station is the most popular as the starting station.
- Usage also drops off in the outskirts.

## 3. Summary:
- It appears that Thursday evenings seem to be the most popular usage time.
- Males on average tend to use the service more than woman.
- Monday and Tuesday are the second most popular days.
- Most trips are used for around 5 minutes.
### For further query:
- 1.) A heatmap that is a mixture of tables 4 and 5. Looking at hourly breakdown based on user type. To see if terminals can be used to advertise subscriptions during ours with high usage from nonsubscribers.
- 2.) A color coded bubble heatmap measuring usages at stations based on user types to see if certain areas are more popular amongst non subscribers to advertise the subsciption as certain stations.
