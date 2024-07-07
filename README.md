---
title: 'Independence days around the world'
author: 'César Heredia, data journalist'
description: 'A detailed look at the dates of the different independence days in 172 selected countries or territories'
modified: '2024-07-05'
files: ['countries_date.csv','per_day.csv','per_month.csv','per_year.csv','per_date.csv','century_decade.csv','independent_from.csv','1900s.csv']
group: 'Miscellaneous'
---

*By César Heredia, data journalist*

The United States celebrated the 248th anniversary of its independence from the Kingdom of Great Britain on July 4. But "America" isn't the only country that gained independence in July. At least 23 out of 172 countries achieved the feat this month, among them Argentina, Belgium, Canada, Colombia, Rwanda, and Venezuela.

Below is the full list of 172 states that obtained independence from 1000 (Hungary) to 2011 (South Sudan):

### Independendence days per country
<FlatUiTable
  data={{
    url: 'countries_date.csv'    
  }}
/>

On **September 15, 1821**, five countries separated from Spain (Costa Rica, El Salvador, Guatemala, Honduras, and Nicaragua). The event is called *Independencia de Centroamérica*, or [Independence of Central America](https://en.wikipedia.org/wiki/Act_of_Independence_of_Central_America). This was the date on which most countries gained their independence. There were four dates on which the independence process was held more than once:

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

However, the day with the most independences (six) is **January 1**. Haiti (1804), Sudan (1956), Cameroon (1960), Samoa (1962), and the Czech Republic (1993) gained sovereignty on the first day of the year. It's followed by the aforementioned September, 15. July, 1, and August 15 count four independence processes each:

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

By months, the ones that belong to the **third quarter of the year** recorded the highest number of independence events of the 172 analyzed in this report, as seen in the next chart:

### Number of independences per month
<PlotlyBarChart
  data={{
    url: 'per_month.csv'
  }}
  title="August is the month with the most country independences"
  xAxis="month"
  yAxis="number"
/>

## 18 countries gained independence in 1960

The 20th century saw an amazing number of **146 declarations of independence**, a sign of how important the 1900 centenary was in world history. Twenty percent of those were held in the 1960s. Only in 1960, 17 Sub-Saharan countries became independent, [mostly from France](https://www.france24.com/en/20100214-1960-year-independence), and Cyprus (from the United Kingdom). In the meantime, 56.8% of processes took place between 1951 and 1980.

### Number of independences in the 20th century
<PlotlyLineChart
  data={{
    url: '1900s.csv'
  }}
  title="1960 and 1991 led the way in the last century before 2000"
  xAxis="year"
  yAxis="number"
/>

Special mentions to the decades of 1820s, when Greece and 11 Latin American countries became independent; the 1910s (15 States), and the 1990s, when the Soviet Union and Yugoslavia disintegrated.

### Number of independences per century/decade
<PlotlyBarChart
  data={{
    url: 'century_decade.csv'
  }}
  title="The 1960s stand out among the rest"
  xAxis="century_decade"
  yAxis="number"
/>

The table below shows the number of independences each year, sorted in descending order. If you want to sort ascendingly, just click on the arrow next to the *year* title.

### Number of independences per year
<FlatUiTable
  data={{
    url: 'per_year.csv'
  }}
/>

## United Kingdom: The ultimate modern empire

Fifty-nine nations reached independence from the United Kingdom between the United States (1776), and Brunei (1984). Twenty-six countries were freed from France since 1804 (Haiti). [Vanuatu gained independence from both the UK and France in 1980](https://www.geeksforgeeks.org/independence-day-of-vanuatu/).

### Independence from...
<PlotlyBarChart
  data={{
    url: 'independent_from.csv'
  }}
  title="Almost 60 countries became independent from United Kingdom"
  xAxis="independence_from"
  yAxis="number"
/>

Twenty States became autonomous from Spain, the majority located in Central and South America, as other 16 countries that belonged either to the Russian Empire (before 1918) or to the Soviet Union (until 1990-91). The disintegration of the USSR marked the [end of the Cold War](https://www.britannica.com/question/How-did-the-Cold-War-end).

##### Source of data: [Independence Days dataset located on Kaggle](https://www.kaggle.com/datasets/rtatman/independence-days)
