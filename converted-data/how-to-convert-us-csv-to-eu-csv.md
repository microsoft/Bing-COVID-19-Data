# Bing COVID-19 data

## Links
https://csvjson.com/csv2json


### Conversion US type CSV to EU (NL) type CSV
1) Excel (Dutch)
Note Data is presented as comma separated

2)  TAB Gegevens > Knop: Text naar Column

3)  Choose 'comma' as delimiter only

4)  [ID]-Column > Choose 'forget'

5)  [Updated]-Column has format MDJ
    Choose *Date  > Select box [MDJ] format

6)  [Confirmed]             Number
    [ConfirmedChange]       Number
    [Deaths]                Number
    [DeathsChange]          Number
    [Recovered]             Number
    [RecoveredChange]       Number

7)  [Latitude]              Text - ADVANCED
    [Longitude]             Text - ADVANCED
    ------------------------------------------------
    [Longitude]- en [Latitude]-Columns
    1) Choose *Text
    2) Choose [Advanced] >
        1) Decimal          > 'comma'-character
        2) 1000 Separator   > 'no'-character

8)  [ISO2]                  Text - STANDARD
    [ISO3]                  Text - STANDARD
    [Country_Region]        Text - STANDARD
    [AdminRegion1]          Text - STANDARD
    [AdminRegion2]          Text - STANDARD

9) Convert








### Conversion: Csv To Json

https://csvjson.com/csv2json


1

### What are the sources of the data?
We collect data from multiple trusted, reliable sources, including the [World Health Organization (WHO)](https://www.who.int/emergencies/diseases/novel-coronavirus-2019), [Centers for Disease Control and Prevention (CDC)](https://www.cdc.gov/coronavirus/2019-ncov/index.html), national and state public health departments, [BNO News](https://bnonews.com/index.php/2020/04/the-latest-coronavirus-cases/), [24/7 Wall St.](https://247wallst.com/), and [Wikipedia](https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic).

### How can I use this data?
This information is available strictly for educational and academic purposes, such as medical research, government agencies, and academic institutions. Data used or cited in publications should include an attribution to 'Bing COVID-19 Tracker' with a link to www.bing.com/covid.

### Why is data missing or inconsistent for some regions
Sources don't always provide counts for all data points, especially recovered case counts. The '-' symbol indicates where data is unavailable. In the dataset published in GitHub, the data field will be blank where data is unavailable.

### Where can I see the latest data?
The most current data available can be found on www.bing.com/covid and in the Bing COVID-19 widget. You can find more information about the Bing COVID-19 widget [here](https://www.bing.com/covid/dev#widget).

### Why is COVID data different on every website?
COVID tracking data comes from a wide set of sources that update at different times and may not always align.

### What about the Bing COVID-19 Widget?
Learn more about the Bing COVID-19 widget [here](https://github.com/microsoft/COVID-19-Widget).

#### Please reach out to BingCovid19DataReqs@microsoft.com for any questions or requests regarding the data.


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
