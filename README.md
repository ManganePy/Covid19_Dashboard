# Covid19_Dashboard
country-by-country data on covid19 deatns, cases, total deaths, new cases etc ...
The data are collected from this csv file 'https://covid.ourworldindata.org/data/owid-covid-data.csv'
Then the csv file loaded to pandas
Two functions are built from this pandas dataframe: 
1) covid_dashboard_V2, to visualize for a given datetime range a given parameter (total cases, total deaths, new cases etc) for given countries.
plotly allows to hide some lines, just clicking on the corresponding legnd
2) map_covid, to visualize a given parameter, at a given date, on a world map
