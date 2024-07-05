---
title: 'Independence days around the world'
author: 'César Heredia, data journalist'
description: 'A detailed look at the dates of the different independence days in 183 selected countries'
modified: '2024-07-05'
files: ['countries_date.csv','per_day.csv','per_month.csv','per_year.csv']
group: 'Miscellaneous'
---

*By César Heredia, data journalist*

#### Independendence days per country
<FlatUiTable
  data={{
    url: 'countries_date.csv'
  }}
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
<LineChart
  data={{
    url: 'per_year.csv'
  }}
  title="1960 and 1991 stand out from the rest"
  xAxis="year"
  yAxis="number"
/>
