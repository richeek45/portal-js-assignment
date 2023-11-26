---
title: 'Indian Population dataset'
author: 'Richeek'
description: 'Dataset of Indian Population'
modified: '2023-05-04'
files: ['indian_population.csv']
group: 'population'
---

Table, mermaid, Vega, VegaLite, LineChart

This is Indian Population

## Chart

<LineChart 
    title="Indian Population by year"  
    xAxis="Birth Rate"
    yAxis="Year" 
    data="indian_population.csv"
/>

<FlatUiTable url="indian_population.csv" />
