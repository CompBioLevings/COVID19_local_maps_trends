# COVID19_local_maps_trends
This is an RMarkdown script/document I created that will auto-download data from multiple sources, do some calculations and generate plots showing the COVID19 trends both nation-wide and for local states/counties over the past two weeks.  Specifically, it generates maps showing COVID death and case rates for the United States and for MN and WI, and dot plots with trendlines showing how COVID case rates are changing locally.  This is all output to an HTML file for easy viewing.

I've included an example HTML file for trends up to January 23rd, 2022.

*Note:* Repository/app is designed to run from the desktop, so either clone the repository to desktop *OR* update the file paths within the code to wherever you placed the repository.

---------------------------------------------------------------------------------------------------

**Data downloaded for use with this application come from multiple sources:**

Data from The New York Times, based on reports from state and local health agencies:
https://github.com/nytimes/covid-19-data/

Data from COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University:
https://github.com/CSSEGISandData/COVID-19

Data from the CDC on vaccination rates:
https://data.cdc.gov/api/views/8xkx-amqh/rows.tsv?accessType=DOWNLOAD&bom=true

---------------------------------------------------------------------------------------------------

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
