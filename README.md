---
title: 'Independence days around the world'
author: 'César Heredia, data journalist'
description: 'A detailed look at the dates of the different independence days'
modified: '2024-07-05'
files: ['countries_date.csv','per_day.csv']
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
