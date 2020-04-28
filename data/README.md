# Bing COVID-19 Data info

## File naming convention 
Bing-COVID19-Data.csv is the static filename for the aggregated COVID-19 case count data 

## Column descriptions 

|Column header | Description | 
|---|---|
|ID | Unique identifier |
|Updated| Datetime in UTC |
|Confirmed | Confirmed case count for the region |
|ConfirmedChange| Change of confirmed case count from the previous day |
|Deaths| Death case count for the region |
|DeathsChange| Change of death count from the previous day |
|Recovered| Recovered count for the region |
|RecoveredChange| Change of recovered case counts from the previous day |
|Latitude| Latitude of the centroid of the region |
|Longitude| Longitude of the centroid of the region |
|ISO2| 2 letter country code identifier |
|ISO3| 3 letter country code identifier |
|Country_Region| Country/region |
|AdminRegion1| Region within Country_region |
|AdminRegion2| Region within AdminRegion1 |

## Update frequency
The data is updated once a day (around 3AM PST).
