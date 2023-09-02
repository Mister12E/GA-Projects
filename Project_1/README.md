# Project 1: Exploring the effect of rainy days on mobile data usage

### Overview

In this project, we will analyze the rainfall and mobile data usage trends in singapore. Preliminary findings show that "On rainy summer weekends, posts receive nearly twice as many reactions: interaction on posts increases by 90%."

(Please contact me via email at: elliottan12@gmail.com should any questions arise)

---

### Problem Statement

As a data scientist from Accenture, we tasked by a digital telco operator, MyRepublic, to embark on a study to find out if singaporeans use more mobile data during quarters with more rainy days?

Knowing the trend, how does a company capitalise on this to capture more market share in the mobile services industry?

---
### External Research

1.) It has been found that the weather has impact on what people do online — most notably what they do via social media.

2.) Bad weather always makes the interaction increase – completely independent from the season.

3.) Fans react, on average, 42% more often when the sun isn’t shining.

4.) On rainy summer weekends, posts receive nearly twice as many reactions: interaction on posts increases by 90%.

5.) Even in spring, autumn and winter. a clear difference between sunny and rainy days is noticeable: there are 39% more reactions on average when it’s rainy.

> [Credit](https://martech.org/why-social-media-marketers-need-to-follow-the-weather/) 

---

### Datasets

I have used 2 datasets that are included in the Data folder for this project. 

* [`rainfall-monthly-number-of-rain-days.csv`](./Data/rainfall-monthly-number-of-rain-days.csv): Monthly number of rain days from 1982 to 2022. A day is considered to have “rained” if the total rainfall for that day is 0.2mm or more.

* [`MobileDataUsage.csv`](./Data/MobileDataUsage.csv): Quarterly amount of mobile data usage from 2004 to 2019. These values are measured in Petabytes. 

These datasets are from [data.gov.sg](data.gov.sg).

---

### Data Dictionary 

|Feature                        | Type   |Dataset   |Description |
|:------------------------------|:-------|:---------|:-----------|
|year                           |integer |merged_df |Years 2005 to 2018 |
|quarter                        |integer |merged_df |The 4 quarters in a year |
|no_of_rainy_days               |integer |merged_df |Number of rainy days in a quarter |
|volume_of_mobile_data          |float   |merged_df |Volumes of mobile data in a quarter in petabytes |
|relative_volume_of_mobile_data |float   |merged_df |Percentage of quarter data usage against the total year's data usage|

---

### Conclusion

Upon examining the rainfall data, a noticeable trend emerges, indicating a higher frequency of rainy days during the final quarter of the year. Correspondingly, mobile data consumption experiences an uptick during the same period. Furthermore, an analysis reveals a positive correlation of 0.39 between these variables.

---

### Recommendations

To enhance customer satisfaction and retention, one strategic option is to provide customers with a data boost during the rainy last quarter. 

Another avenue for consideration is to implement enticing promotional campaigns during periods of increased rainfall, thereby seizing a larger share of the market.

---

### Limitations And Future Work
In the course of this project, I encountered a notable constraint – the scarcity of data. With access to comprehensive datasets encompassing daily rainfall and mobile data usage, our analysis could have yielded a more precise insight into whether Singaporeans exhibit an increased mobile data usage tendency during rainy days.

Subsequent endeavors could encompass the exploration of diverse datasets, such as the daily count of festivals and events, in order to discern if a stronger correlation emerges. Upon identifying the most strongly correlated feature, an extended investigation could involve cross-referencing data from other countries to ascertain if similar trends manifest globally.