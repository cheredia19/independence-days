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

#### Independendence days per country
<FlatUiTable
  data={{
    url: 'countries_date.csv'    
  }}
/>

#### Timeline of independence days
<PlotlyLineChart
  data={{
    url: 'per_date.csv'
  }}
  xAxis="exact_date"
  yAxis="number"
/>

#### Number of independences per day
<PlotlyBarChart
  data={{
    url: 'per_day.csv'
  }}
  title="January 1 is the day with the most country independences"
  xAxis="date"
  yAxis="number"
/>

#### Number of independences per month
<PlotlyBarChart
  data={{
    url: 'per_month.csv'
  }}
  title="August is the month with the most country independences"
  xAxis="month"
  yAxis="number"
/>

#### Number of independences per year
<FlatUiTable
  data={{
    url: 'per_year.csv'
  }}
/>

#### Independence from...
<PlotlyBarChart
  data={{
    url: 'independence_from.csv'
  }}
  title="Almost 60 countries became independent from United Kingdom"
  xAxis="independence_from"
  yAxis="number"
/>

#### Number of independences per century/decade
<PlotlyBarChart
  data={{
    url: 'century_decade.csv'
  }}
  title="The 1960s stand out among the rest"
  xAxis="century_decade"
  yAxis="number"
/>
