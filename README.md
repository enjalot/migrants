# The Migrant Files

[The Migrant Files](http://themigrantfiles.com) project has been collecting data about the ongoing refugee crisis in Europe. 


## Deaths
Events during which someone died trying to reach or stay in Europe  
`events.csv` [source spreadsheet](https://docs.google.com/spreadsheets/d/1YNqIzyQfEn4i_be2GGWESnG2Q80E_fLASffsXdCOftI/edit#gid=1085726718)  

[Example code with d3](http://blockbuilder.org/enjalot/7ea44d0bc364b6bddbd8)
```js
d3.csv("http://enjalot.github.io/migrants/events.csv", function(err, rawdata) { ... })
```

## Deportations
The source spreadsheet has more information on the breakdown of costs per country
`deportations-year-country.csv` [source spreadsheet](https://docs.google.com/spreadsheets/d/1rDThuJ1HVTsWWPEvauOIGuY0kd7h8fGkrxebmlMt7h4/edit#gid=0)  

[Example code with d3](http://blockbuilder.org/enjalot/d6696d28fb47fcf8a537)
```js
d3.csv("http://enjalot.github.io/migrants/deportations-year-country.csv", function(err, rawdata) { ... })
```

## Money
The amount of money spent by refugees attempting to migrate to Europe
`money.csv` [source spreadsheet](https://docs.google.com/spreadsheets/d/1cynO8lp6crS4p9kJZUqYUigEB15F2cAwGm7aD9cwoZU/edit#gid=0)  

The source spreadsheet details the methodology as well as provides summary statistics

[Example code with d3](http://blockbuilder.org/enjalot/d6a92a077e78fd33316a)
```js
d3.csv("http://enjalot.github.io/migrants/money.csv", function(err, rawdata) { ... })
```


## Inspiration
The Migrant Files [homepage](http://themigrantfiles.com) has several nice d3.js visualizations

Migrant Deaths mapped with [d3.geo.tile](http://bl.ocks.org/boeric/47aceae44bb5f8b63d7b)  
Migrant Deaths mapped with [d3 + Leaflet + Crossfilter](http://bl.ocks.org/shobhitg/60eec0e1727c6c628728)  

## Tools

Quickly put together d3 based map with [DataMapper](http://datamaps.github.io/)  

## Contextual datasets

`countries.csv`
Extracted from the [Natural Earth Dataset](http://www.naturalearthdata.com/)  
[Example code with d3](http://blockbuilder.org/enjalot/6281f8a4ef5967c74ebe)
