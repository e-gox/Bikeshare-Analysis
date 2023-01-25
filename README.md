# Bikeshare-Analysis
1. Business task - Determine the meterics that make causual riders unique from members and how to inrease revenue.   
2. Data sources - The previous 6 months of historical data was acquired from Cyclistic and consolidated in to one dataframe via Python. 
3. Data cleaning and manipulation - The dataframe originally contained 13 columns after determining necessary variables this was reduced to 5. In order to determine how long each rider was using the product the "started_at" and "ended_at" columns were converted in to the datetime datatype. The ride length was than converted in to a integer calculated in minutes. A new column weekday was added. Data was vetted for null values, however none was found.
4. Summary - Casual riders were more activate on weekends oppossed to members who were more activate on weekdays. On average casual riders spent a longer duration of time on bikes than members did. This is likely due to members using services for work transportation oppossed to casual riders who use it for more leisurely activities.
5. Supporting visualizations - 
![image](https://user-images.githubusercontent.com/112779850/214485314-3dff1a5b-d9d6-4609-ab0e-f727054bdd9e.png)
![image](https://user-images.githubusercontent.com/112779850/214485341-da3b73c8-ff3e-4b6d-8173-e10d78a2e9e7.png)
6. Recommendations - My first recommendation is to increase costs of long duration bike usage. According to "Average Duration per Day" graph casual riders double the time on bikes oppposed to members on a day to day basis. This will increase incentive to become a member for the casual rider.
My second recommendation is to create a weekend only membership specifically to target casual riders. According to the above graphs there are more casual riders on the weekends and they also use the bikes for longer durations. 
