---
title: "Case Increase Trends by County"
author: "Kara Haberstock Tanoue"
date: "7/08/2020"
output: 
  html_document:
    theme: paper
    highlight: kate
---



## 7-Day Average Daily Case Increases in Arizona Counties

Average daily case increases are on an upward trend in most counties in Arizona.
  
Note that typically it takes 10-14 days to see the effects of major policy changes or events. This is due to both the incubation period of COVID-19 (median of 4-5 days between exposure and symptom onset according to the CDC) and the reporting lag for new case data (typically 4-7 days according to ADHS).  
  
#### Key Dates in Arizona  

**03/15**: Schools Close  
**03/31**: Stay at Home Order goes into effect  
**04/23**: Testing Expands  
**05/15**: Stay at Home Order expires  
**05/25**: Memorial Day  


preserveae53c5788666695c

### Data & Methods:

County data on COVID-19 case counts are drawn from the New York Times COVID-19 Data Repsitory, accessed at [https://github.com/nytimes/covid-19-data](https://github.com/nytimes/covid-19-data). The 7-Day Average Daily Case Increase variable is a derived variable obtained by averaging the new cases added each day over a rolling 7-day window. A 7-day window was used as there are strong day of the week effects in data reporting. These data were last updated on 07.07.2020 
  
**Data analyzed and visualized by [Kara Haberstock Tanoue](https://www.karatanoue.com).**

### Other Dashboards Worth Following:

**[COVID Risk Levels](https://globalepidemics.org/key-metrics-for-covid-suppression/)**: Provides county-level risk levels based on population-normalized case growth  
**[COVID Act Now](https://covidactnow.org)**: Provides a model of infection rates and key metrics for states and counties across the U.S.  
**[COVID Racial Data Tracker](https://covidtracking.com/race)**: Provides data on race & ethnicity for COVID-19 cases across the U.S. and tracks racial and ethnic disparities in cases and deaths. 
