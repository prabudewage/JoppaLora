# Data Analysis in Joppa City
Analyzing LoRa and Central nodes data in Joppa city
* Two LoRa sensors, Node-53 (North) and Node-54 (South) were deployed in Joppa city in 2022 April 16.
* LoRa-53: latitude = 32.7160 & longitude = -96.7504
* LoRa-54: latitude = 32.7104 & longitude = -96.7472
* Central Node: latitude = 32.7153 & longitude = -96.7479

### 1. UTC_AvgDF
Raw data is in UTC time. Average data per 10 minutes and hourly. Save two dataFrames of 10 minutes and Hourly.

### 2. Local_AvgDF
Convert all three dataFrames from UTC time to Local (Texas) time. Average all three dataFrames per 10 min, hourly and daily. Add day name for all three dataFrames and save.

### 3. Plots
Scripts of scatter plots bar charts and grib visualization