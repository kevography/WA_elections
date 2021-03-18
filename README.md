# [Washington State Election Dashboard]()
#### by Kevin Chau

## Project Description

An interactive webmap that provides on-the-fly data visualizations of the voting patterns of Washington State Counties. This dashboard provides a look at the political makeup of Washington state inhabitants and contextualizes the 2020 election in terms of voting trends and habits. Users are able to click on individual counties to analyze their specific trends and form their own analyses. The data visualizations will change in response to users' selection and analyze such aspects like the proportional breakdown of votes as well as that county's voting history and the history of third party voters.

## Project Goals

I think Washington state is perceived by many living outside its boundaries as a solidly liberal area in terms of its politics. Living inside the state I am well aware of the ways that this perception can be wrong. This project at times is my attempt to emulate the electoral broadcast maps and an invitation to explore the ways Washington state differs within its own boundaries. I wanted to challenge that perception and at the same time contextualize it within its own voting patterns and smaller voting blocs.

## Data Sources

- Election Data: Washington Secretary of State Election results
    - [2008 Election](https://results.vote.wa.gov/results/20081104/export.html)
    - [2012 Election](https://results.vote.wa.gov/results/20121106/export.html)
    - [2016 Election](https://results.vote.wa.gov/results/20161108/export.html)
    - [2020 Election](https://results.vote.wa.gov/results/20201103/export.html)
- Geographic Data: [United States Census Bureau County Boundaries](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html)

## Applied Libraries, Web Services, and Programs

- Leaflet - Building webmap features
- CartoDB - Basemap Source
- C3 - D3-based API used to build data visualizations
- JQuery - event handling and manipulation
- GitHub - Web hosting service for files
- QGIS and QMetaTiles - Used to compile geographic data and export usable GeoJSON files

## Acknowledgements

This project was created as part of the University of Washington's Geography 458 course under Professor Bo Zhao with assistance from teaching assistant Tyler McCrea. Professor Zhao also provided much of the boilerplate code for the smart dashboard template.
