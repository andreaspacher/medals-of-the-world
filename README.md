# Medals of the World

This project webscrapes data from the website [Medals of the World](https://medals.org.uk/).

_Medals of the World_ is a website which serves as the most comprehensive, freely available source of information about honorific orders, political medals and state awards.

The scripts are the following:

 - `01_scrape_links.R`: Scrape the links to each respective list of polities.
 - `02_scrape_medals.R`: Gather the links to each polity’s medals.
 - `03_scrape_years.R`: For each medal, scrape the name and the year of establishment.
 - `04_add_continent_and_harmonize_countries.R`: Structure the data into a table that includes the name of the respective polity or country. Harmonize the names manually, and then automatically attribute the polities or countries to continents.
 - `05_plot.R`: Some basic examples for data visualizations and analyses.


