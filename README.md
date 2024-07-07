---
title: 'Independence days around the world'
author: 'César Heredia, data journalist'
description: 'A detailed look at the dates of the different independence days in 172 selected countries or territories'
modified: '2024-07-05'
files: ['countries_date.csv','per_day.csv','per_month.csv','per_year.csv','per_date.csv','century_decade.csv','independence_from.csv',]
group: 'Miscellaneous'
---

*By César Heredia, data journalist*

The United States celebrated the 248th anniversary of its independence from the Kingdom of Great Britain on July 4. But "America" isn't the only country that gained independence in July. At least 23 out of 172 countries achieved the feat this month, among them Argentina, Belgium, Canada, Colombia, Rwanda, and Venezuela.

Below is the full list of 172 states that obtained independence from 1000 (Hungary) to 2011 (South Sudan).

### Independendence days per country
<FlatUiTable
  data={{
    url: 'countries_date.csv'    
  }}
/>

On September 15, 1821, five countries separated from Spain (Costa Rica, El Salvador, Guatemala, Honduras, and Nicaragua). The event is called *Independencia de Centroamérica*, or [Independence of Central America](https://en.wikipedia.org/wiki/Act_of_Independence_of_Central_America). This was the date on which most countries gained their independence. There were four dates on which the independence process was held:

 - May 28, 1918: Armenia and Azerbaijan declared independence from the Russian Empire.
 - August 15, 1945: North, and South Korea.
 - October 01, 1960: Cyprus, and Nigeria (the former gained independence from the United Kingdom on August 16, but is commonly celebrated on October 1).
 - July 1, 1962: Burundi and Rwanda regained independence from Belgium.


### Timeline of independence days
<PlotlyLineChart
  data={{
    url: 'per_date.csv'
  }}
  xAxis="exact_date"
  yAxis="number"
/>

## New year, new beginning

However, the day with the most independences (six) is January 1. Haiti (1804), Sudan (1956), Cameroon (1960), Samoa (1962), and the Czech Republic (1993) gained sovereignty on the first day of the year. It's followed by the aforementioned September, 15. July, 1, and August 15 count four independence processes each:

-  July 1: Canada (1867), Somalia (1960), Burundi and Rwanda (1962).
-  The Koreas (1945), India (1947), and Republic of the Congo (1960).

### Number of independences per day
<PlotlyBarChart
  data={{
    url: 'per_day.csv'
  }}
  title="January 1 is the day with the most country independences"
  xAxis="date"
  yAxis="number"
/>

By months, the ones that belong to the third quarter of the year have the highest number of independence events of the 172 analyzed in this work, as seen in the next chart:

### Number of independences per month
<PlotlyBarChart
  data={{
    url: 'per_month.csv'
  }}
  title="August is the month with the most country independences"
  xAxis="month"
  yAxis="number"
/>

### Number of independences per year
<FlatUiTable
  data={{
    url: 'per_year.csv'
  }}
/>

### Number of independences per year
<PlotlyBarChart
  data={{
    url: 'per_year.csv'
  }}
  xAxis="month"
  yAxis="number"
/>

### Number of independences per century/decade
<PlotlyBarChart
  data={{
    url: 'century_decade.csv'
  }}
  title="The 1960s stand out among the rest"
  xAxis="century_decade"
  yAxis="number"
/>

### Independence from...
<PlotlyBarChart
  data={{
    url: 'independence_from.csv'
  }}
  title="Almost 60 countries became independent from United Kingdom"
  xAxis="independence_from"
  yAxis="number"
/>
