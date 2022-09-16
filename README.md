# CWRUBootcamp_M5_09062022_PyBer_Hoynacke
Module 5 - PyBer Python and MatPlotlib

## Overview of Project 

Project includes analyzing all the rideshare data from January to early May of 2019 and create a compelling visualization for the CEO, V. Isualize.
V. Isualize has given me a brand-new assignment. Using my Python skills and knowledge of Pandas, I created a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, I created a multiple-line graph that shows the total weekly fares for each city type. 

## Deliverable 1 Results 

1. The total number of rides for each city type.

<img width="665" alt="Screen Shot 2022-09-15 at 7 57 54 PM" src="https://user-images.githubusercontent.com/111096384/190528619-12e8a743-4a8a-4ffd-92cd-25af6265b929.png">

2. The total number of drivers for each city type.

<img width="711" alt="Screen Shot 2022-09-15 at 7 58 59 PM" src="https://user-images.githubusercontent.com/111096384/190528715-fb1a0358-40bf-4cf5-9bb5-6218bcaea0bd.png">

3. The sum of the fares for each city type.

<img width="721" alt="Screen Shot 2022-09-15 at 7 59 55 PM" src="https://user-images.githubusercontent.com/111096384/190528823-d1b86fb8-2b98-4c6e-9b0c-906b875f15b6.png">

4. The average fare per ride for each city type.

<img width="717" alt="Screen Shot 2022-09-15 at 8 00 40 PM" src="https://user-images.githubusercontent.com/111096384/190528887-4672407e-4192-4514-bb4f-47b39aa0cec1.png">

5. The average fare per driver for each city type

<img width="728" alt="Screen Shot 2022-09-15 at 8 02 13 PM" src="https://user-images.githubusercontent.com/111096384/190529030-6cc99d9b-221b-48b8-93ba-a5ade5f514af.png">

6. The PyBer summary DataFrame formatted

<img width="717" alt="Screen Shot 2022-09-15 at 8 03 24 PM" src="https://user-images.githubusercontent.com/111096384/190529132-0810574c-9f60-4abe-9fe1-edb87a117759.png">

## Deliverable 2 Results 
1. A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.

<img width="716" alt="Screen Shot 2022-09-15 at 8 06 40 PM" src="https://user-images.githubusercontent.com/111096384/190529432-837f100a-f40b-4cea-bef7-1c75bb9a4ab6.png">

2. A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare." 

<img width="739" alt="Screen Shot 2022-09-15 at 8 09 34 PM" src="https://user-images.githubusercontent.com/111096384/190529704-60aa380d-e066-43e3-a443-c343f3972db5.png">

3. A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-29. 

<img width="723" alt="Screen Shot 2022-09-15 at 8 13 39 PM" src="https://user-images.githubusercontent.com/111096384/190530002-68d8c87a-92e2-4763-a53c-98a5e896e969.png">

4. A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.

<img width="728" alt="Screen Shot 2022-09-15 at 8 14 41 PM" src="https://user-images.githubusercontent.com/111096384/190530096-735db0f0-c259-4dc4-9ccf-d664811a61d5.png">

5. An annotated chart showing the total fares by city type is created and saved to the "analysis" folder. 

<img width="633" alt="Screen Shot 2022-09-15 at 8 15 11 PM" src="https://user-images.githubusercontent.com/111096384/190530149-f0020a27-56cd-4051-9913-cfeee41303d0.png">

## Summary of Results and Reccommendations 

#### Statement summarizing three business recommendations to the CEO for addressing any disparities among the city types

 1. Opportunity to expand the ride share bussiness in rural and suburban areas. 
 2. More attention needs to be given to the rural area. Promotions should be considered to encourage riders to use ride share in rural areas.
 3. Urban riders are consistently riding and is the biggest demographic using ride sharing. It is clearly a high demand service meaning that fares could     rise without losing customers and more drivers can be hired. 
