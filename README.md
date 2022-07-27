# JoppaLora
Analyzing LoRa and Central nodes data in Joppa city
* LoRa-53: latitude = 32.7160 & longitude = -96.7504
* LoRa-54: latitude = 32.7104 & longitude = -96.7472
* Two LoRa sensors, Node-53 (North) and Node-54 (South) were deployed in Joppa city in 2022 April 16.

### 1. 10min_avg_lora_df
* Average two LoRa sensors data per 10 min and make two dataframes.

### 2. 10min_avg_central_df
* Average Central Node data per 10 min and make a single dataframe.

### 3. local_10min_hourly_daily_avg_with_dayname_df
* Convert all three dataFrames from UTC time to Local (Texas) time.
* Average all three dataFrames per 10 min, hourly and daily.
* Add day name for all three dataFrames and save

### 4. plot_10min_hourly_daily_PM2_5_together
* Plot 10 min averaged PM2.5 for all the data of three sensors together. 
* Plot hourly averaged PM2.5 for all the data of three sensors together. 
* Plot daily averaged PM2.5 for all the data of three sensors together. 

### 5. plot_PM2_5_with_dayname_bar
* Use daily averaged PM2.5 dataFrames of all three sensors.
* Group by day names.
* Plot each group data of a sensor on a scatter plot together. 
* Get average of each group. 
* Plot bar chart of averaged-PM2.5 vs day-name.

### 4. vizualize_wind_data
* Visualize wind data downloaded from ECMWF.
* Visualize sensor locations on the same plot.
