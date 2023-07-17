
# Uber Data Analytics | Modern GCP and Mage-ai Data Engineering Project

The project aims to perfrom data analytics on uber data set using various tools and techniques.


## Tech and Tools

**Cloud:** Google cloud stroage

**Instance:** Google Computing Engine

**Data pipeline tool:** Mage-ai

**Analytics:** BigQuery

**Dashboard:** LookerStudio


## Data Set

- Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

- Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf


The fiels in the data set captures  pick-up and drop-off locations, pick-up and drop-off dates/times, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`API_KEY`

`ANOTHER_API_KEY`


## Flow

1)The uber data-set was uploaded to google cloud storage.

    https://storage.googleapis.com/uber_data_sibiakash/uber_data.csv


2)A virtual computing engine was created and mage-ai instance was deployed on it.


3)Using mage-ai a standard ETL datapipeline was created which was exported onto Bigquery.


4)Bigquery was used to perform data analysis and final analytics table was created.

    console.cloud.google.com/bigquery?ws=!1m5!1m4!4m3!1suberproject79!2suber_engproject!3stbl_analytic


5)The analytics table was pushed to lookerstudio for creating a dashboard.



