# Weather-Anomoly-detection
The weather data consist of temperature data and rain amounts from a 1 year period and the same 
stats from past dates including the highest rain and temperature values recorded.
I explain my thought process and analysis of approaching weather anomalies according to temperature and rain amounts in the notebook.

### A basic bar chart showing ammount of rainfall
* Feb has the lowest amount of rain fall
* Jun has the highest amount of rain fall
![image](https://user-images.githubusercontent.com/65574434/194699951-e07aff95-ffcc-4bce-825f-36314f069c18.png)

### Simple scatter plot showing some isolated scatters implying anomaly
* Histograms show volume in months and an average amount of rain volumes
![image](https://user-images.githubusercontent.com/65574434/194699977-834ab5a4-8390-4ec5-b960-4e13faa42937.png)

### Basic line chart plotting current year observed and highest recorded amount
* Large peaks identifying anomalies
* September with the most rainfall recorded in a day
* Also june with strong spikes and high volume of rainy days
![image](https://user-images.githubusercontent.com/65574434/194699971-6b8dfd52-a162-435d-b965-87872b3c611b.png)

### Line graph detecting rainy days above the average high
* Typically spikes above the line may be considered above average rainfall
![image](https://user-images.githubusercontent.com/65574434/194700319-5723b10b-f574-4abc-993f-46a7471d0b64.png)

### Above average 8x & 10x
* data was copied and data was dropped if above the calculated amount and plotted to show these graphs 
![image](https://user-images.githubusercontent.com/65574434/194700478-91455869-c203-40e7-9704-eba4da9ee3b7.png)
![image](https://user-images.githubusercontent.com/65574434/194700483-0550f28b-bf85-45bc-9f21-7584a224f12f.png)

### outside the 95th percentile Anomaly  
* approximately more than 3.8m of rainfall is most certainly extreme anomaly
![image](https://user-images.githubusercontent.com/65574434/194700606-987201bb-d66b-4dfa-93a7-6d711e75b4c1.png)

### Isolation forest
![image](https://user-images.githubusercontent.com/65574434/194700756-67f759f2-8499-4a0a-b5e5-9d42c762316d.png)

### DBScan
![image](https://user-images.githubusercontent.com/65574434/194700818-94e86dda-aa86-4163-816a-88386fa4d3b4.png)

### Data Visualization
![image](https://user-images.githubusercontent.com/65574434/194700855-919cac4a-61d0-4c61-9e4b-7be5495e5bcb.png)
![image](https://user-images.githubusercontent.com/65574434/194700864-83a957ec-c32a-42e9-81e3-289542e55a56.png)
![image](https://user-images.githubusercontent.com/65574434/194700869-07930c62-0225-4e75-b7de-58c760f1e0ee.png)



