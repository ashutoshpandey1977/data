# Overview
This dataset comprises comprehensive records that include detailed information about various cities, countries, significant dates, organizations, and individuals. Each entry is meticulously verified against Wikidata to ensure accuracy and reliability. The dataset is enriched with additional attributes, offering valuable insights into historical events, cultural significance, geographical coordinates, environmental data, and much more. This makes the dataset highly suitable for geographical analysis, historical research, data-driven decision-making, and academic purposes. By providing a structured and enriched set of data, it aims to be a valuable resource for analysts, researchers, and professionals across various fields.

# File Format
The dataset is stored in a spreadsheet CSV format for easy access and analysis.
# Data Dictionary

| Column Name          | Data Type | Description | Example |
|----------------------|----------|-------------|---------|
| City                | String   | Name of the city mentioned in the dataset. Used for geographic enrichment. | Nur-Sultan |
| Country             | String   | Name of the country corresponding to the city. | Kazakhstan |
| Title               | String   | Title of the article or entity extracted from the data source. | Polish Open (tennis) |
| Link                | String   | URL to the original article or webpage. | [Polish Open](https://en.wikipedia.org/wiki/Polish_Open_(tennis)) |
| Extracted Years     | String   | Years extracted from the content, representing historical references. | 2011, 2018 |
| People              | String   | Names of people, enriched with Full Name,Birth Date,Nationality,Occupation,Notable Achievements, Summary.| Full Name: Sarla Bedi \| Birth Date: 1925-04-04T00:00:00Z \| Nationality: Canadian \| Occupation: Religious priestess of Arya Samaj \| Notable Achievements: Establishing Arya Samaj in Toronto, Canada \| Summary:  \|
| Organization        | String   | Names of organizations mentioned, enriched with founding date, industry, headquarters, and key personnel. | BNP Paribas \| Founded: 1848 \| HQ: Paris \| Industry: Banking \| Key Personnel: Jean-Laurent Bonnafé |
| Locations           | String    |Locations extracted from the content| Washington Gardens |
| Coordinates         | String   | Latitude and longitude of the city, obtained from Wikidata or OpenStreetMap. | Latitude: 51.1282205, Longitude: 71.4306682 |
| Wikipedia Summary   | String   | Brief Wikipedia summary of the city or topic for context enrichment. | Astana, formerly known as Nur-Sultan... (truncated) |
| Wikipedia Link      | String   | Direct link to the Wikipedia page of the city or entity for further reference. | [Astana Wikipedia](https://en.wikipedia.org/wiki/Astana) |


# Usage

* This enriched dataset provides comprehensive information about locations, people, and organizations, making it valuable for geographical analysis, historical research, data-driven decision-making, academic purposes, and more.

* Use the provided coordinates for mapping and spatial analysis.

* Explore the additional attributes for deeper insights into the historical, cultural, and environmental context of each record.
