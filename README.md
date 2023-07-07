# Analysis of Foreign Pupils in Poland

This project aims to analyze the distribution and characteristics of foreign pupils studying in Poland. It explores the regional distribution, country of origin, and concentration in major cities. The analysis utilizes geospatial data and visualizations to provide insights into the educational landscape of foreign pupils in Poland.

## Data

The analysis is based on a dataset of foreign pupils studying in Poland. The dataset includes information such as the number of pupils, their country of origin, and the region they are studying in. The data is loaded from a CSV file.

### Data source:

Dataframe taken from [open data resource](https://dane.gov.pl/pl).

World map source - [natural earth](https://github.com/nvkelso/natural-earth-vector/blob/master/geojson/ne_10m_admin_0_countries_ukr.geojson)

Map of [Polish Voivodeships](https://github.com/andilabs/polska-wojewodztwa-geojson/blob/master/polska-wojewodztwa.geojson)
## Analysis

The analysis begins with data preprocessing and exploratory data analysis to understand the structure and content of the dataset. The code covers tasks such as checking for missing values, renaming columns, and summarizing the data.

Next, the analysis examines the regional distribution of foreign pupils in Poland. It calculates the total number of pupils by voivodeship and visualizes the results on a map using geospatial data.

The analysis also explores the country of origin of the foreign pupils. It categorizes the pupils based on their country of origin, calculates the total number of pupils for each country, and presents the top countries with the highest number of pupils.

Finally, the analysis focuses on the concentration of foreign pupils in major Polish cities. It identifies the cities with the highest number of foreign pupils and presents the results in a bar chart.

## Conclusions

The analysis reveals several key findings:

- Regional Distribution: The Mazovian, Lower Silesian, and Greater Poland voivodeships have the highest concentration of foreign pupils in Poland.

- Country of Origin: The largest number of foreign pupils in Poland come from Ukraine, Belarus, Russia, Vietnam, and India.

- Concentration in Major Cities: Warsaw, Wrocław, and Kraków are the cities with the highest number of foreign pupils in Poland.

These findings provide valuable insights into the distribution and characteristics of foreign pupils in Poland. The information can be useful for educational institutions and stakeholders in developing strategies to support and enhance the educational experience of international pupils.

Please refer to the code and visualizations in this project for more details and a comprehensive understanding of the analysis.

## Note:  Due to the interactive nature of a geospatial map included in the project, they may not be fully visible in the static format. However, you can access the complete project, including the interactive map and code execution, by clicking on the [following link.](https://colab.research.google.com/drive/1BrbNsgXkp2vuoBSN3bF_mejSQEOjyV2x?authuser=1#scrollTo=f557b78c) This will allow you to explore the project in its entirety and interact with the visualizations. Please follow the link to access the full project.
