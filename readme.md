<h1> Driving Licenses, Traffic Accidents and Casualties Analysis </h1>

<h3> About The Project </h3>
Analysis two databases, the first one is driving licenses from 1993 to 2017 and the second one is traffic accidents in 2016 and 2017 in Saudi Arabia. I will work on Python, statistics, EDA and visualizations, then I will mention the top cities in the number of driving licenses and traffic accidents and relationship between each other, finally I will mention some recommendations.



<h3> Datasets </h3>

- [Traffic Accidents and Casualties by Region](/data/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008.csv)
- [Driving Licenses Issued By Administrative Area](/data/saudi-arabia-driving-licenses-issued-in-the-kingdom-2004-2008.csv)

You can see the source for the accident data [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/), and the source for the license data [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/). 

A quick overview on two datasets'  features / variables / columns, alongside data types and descriptions

| Feature            | Type   |Dataset   |Description |
|--------------------|--------|----------|------------|
|year|int64|licenses|The year on which a number of driving licenses were issued|
|region|object|licenses|The region on which a number of driving licenses were issued|
|no._of_liceses|int64|licenses|The number of driving licenses were issued on a year at a region|
|license_longitude|float64|licenses|The longtitude of the region|
|license_latitude|float64|licenses|The altitude of the region|
|year|int64|accidents|The year on which a record of accidents took place|
|region|object|accidents|The region on which a record of accidents took place|
|indicator|object|accidents|The indicator of the accidents(number of casualties dead, number of casualties injured, number of accidents)|
|no._of_ndicators|int64|accidents |The amount of the indicator|
|accident_longitude|float64 |accidents |The longtitude of the region|
|accident_latitude|float64 |accidents |The altitude of the region|

<h3>Conclusion</h3>
 There is a strong relationship between the number of licenses issued and the number of accidents. Also Riyadh, Makkah and Eastern are the trend in number of driving licenses and traffic accidents and they have the highest population in Saudi Arabia for more details kindly go to the 
<a href="https://medium.com/@shehanaaljloud/https-medium-com-shehanaaljloud-driving-licensesـtraffic-accidents-f43d6a1dc56a">Blog</a>

