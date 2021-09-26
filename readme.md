# Ford GoBike System Data Exploration
![Intro Image](https://1.bp.blogspot.com/-nzMT6LTD4s8/YU_serSfsyI/AAAAAAAADbQ/vgrKt6vTOkojbRSpMWT82K1J1-n8_IM5wCLcBGAsYHQ/s16000/Yellow%2BBlue%2Band%2BOrange%2BAbstract%2BPatterns%2BBuyer%2BPresentation%2BListing%2BPresentation.png)
## Dataset

Dataset Overview

Bay wheels -previously Ford GoBike- is large-scale bicycle sharing system deployed in California and on the West Coast of the United States ,Bay wheels like have a large fleet of sturdy and durable bikes that can be used then be locked into a docking station from the huge network of docking stations that are distributed throughout the city.The dataset used for this exploratory analysis is the newest published dataset as of Jul 6th 2020, 02:29:56 am , you can find it here : https://s3.amazonaws.com/baywheels-data/202006-baywheels-tripdata.csv.zip .

    The dataset originally includes 158168 Trips with 13 attributes / columns:
    -ride_id
    -rideable_type -started_at -ended_at
    -start_station_name
    -start_station_id
    -end_station_name
    -end_station_id -start_lat
    -start_lng
    -end_lat
    -end_lng
    -member_casual

    With the new five attributes/features I added :
    -ride_duration
    -year
    -month
    -day -weekend
    the total will be 18 attributes

## Summary of Findings

In the exploration, I found that there was a strong relationship between the bike type and the duration of the ride where electric bikes are used for short duration trips while docked bikes are always used for long duaration trips , also there's a relation between trips and days of month where days like 13 ,7 are the most crowded days , Also i found that long duration trips are usually done in the first 10 days of them month and decreases and tend to increase again at 20s of the month and tend to decrease again while we are approching the end , also found that big parts of the trips are done in non-wwekend days which is very surprisingly 
## Key Insights for Presentation

For the presentation, I focus on just the influence of the five main points on trip which is day of month , is the day weekend , The customer(rider) membership also the ride (bike) types effect and finally the duration of trip , then i summarized my findings in multvariate graphs to make my ideas very clear
