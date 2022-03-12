# bikesharing

We are tasked with analyzing the Citibike data and put together a "proof of concept" business proposal.

We seek to create a trip analysis that will help key stakeholders decide on the investment.

The proposal is powered by Tableau to answer questions using data.

Following are questions we provide visual answers to:

How long bikes are checked out for all riders and genders.
How many trips are taken by the hour for each day of the week, for all riders and genders.
A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

## Link to Tableau Storyboard

[Tableau Story](https://public.tableau.com/app/profile/rebecca.hinkle/viz/Bikesharing_16471037981810/Story1?publish=yes)

# Cleaning the Data:

Jupyter Notebook was used to change the trip duration data to a datetime field.

<img width="1338" alt="Deliverable 1" src="https://user-images.githubusercontent.com/94575416/156950377-bd1a06b6-4465-445a-8e19-8756238e2118.png">

## Results of the Citibikes Analysis:

### 1. Checkout Times for All Users

The Citibikes usage reaches a high of 3000 minutes.

<img width="1433" alt="0_User" src="https://user-images.githubusercontent.com/94575416/158029865-fb9991c1-4d4c-4bdf-8abc-bf3cea5c4775.PNG">

### 2. Checkout Times per Gender

Males are more likely to use the bikes than any other user.

<img width="1440" alt="1_Gender" src="https://user-images.githubusercontent.com/94575416/158029888-a972fce5-4ba2-4ae0-a13e-867fb9b72e73.PNG">

### 3. Trips (Weekday per Hour)

0600-1000 and 1500-2000 are peak riding hours during the weekday and 0500-1000 on the weekends.

<img width="1392" alt="2_Trips" src="https://user-images.githubusercontent.com/94575416/158029896-491488ab-6126-48af-9350-39fac6ce8fdb.PNG">

### 4.Trips by Gender by Weekday per Hour

Males are the highest users during the peak hours.

<img width="1428" alt="3_TripGender" src="https://user-images.githubusercontent.com/94575416/158029909-e89571a4-301f-4f70-84db-ab5aae05065d.PNG">

### 5. Trips by Gender and User Type

Male subscribers are the highest users.

<img width="1429" alt="4_UserType" src="https://user-images.githubusercontent.com/94575416/158029973-cb0872ff-3fa7-425d-8d5d-fd851c9ccbc7.PNG">

### 6. Number of Rides per Hour

Non peak hours are 0100-0500.

<img width="831" alt="Number of Rides per Hour" src="https://user-images.githubusercontent.com/94575416/156950407-ff69f79a-ae2b-498e-aacc-c3bd75494c19.png">

### 7. Number of Rides with Bike ID

The divergence line shows that there are high usage on 1/3 of the bikes.


# Summary

With the data, we were able to answer all of the questions regarding proof of concept. We identified peak demand service hours, busiest days and also performed a deep dive into the users to get a feel for the services appeal. Bike repairs should be done during non peak hours. We found that male subscribers are the highest users. 

# Additional Analysis

### 1. Ride Starting Locations by Gender
Males are more likely to start a trip farther than the main city center.

<img width="1438" alt="7_Start" src="https://user-images.githubusercontent.com/94575416/158030321-bd2723d4-c10c-4f98-b2a4-a88d7a5250cc.png">

### 2. Ride Ending Locations by Gender

Males are the only gender that ended a trip across the river.

<img width="1430" alt="8_End" src="https://user-images.githubusercontent.com/94575416/158030358-303f9c60-fba8-436a-a85f-a5c4abe7fa6b.png">

### 3. Subscribers are more likely to start a trip farther than the main city center.

<img width="1401" alt="9_UserStartLoc" src="https://user-images.githubusercontent.com/94575416/158030396-030b3072-3e54-45c1-aad4-0c15351c093d.png">

While the data is insightful, more information is needed to determine if the service will appeal to potential users there. 
Age is a factor in the services appeal to users and comparing the age of residents would be insightful.
