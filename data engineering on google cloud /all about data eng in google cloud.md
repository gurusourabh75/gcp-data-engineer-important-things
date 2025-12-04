 A data engineer builds data pipelines to enable data-driven decisions

• Get the data to where it can be useful ---> raw data ingestion and storage

• Get the data into a usable condition---->data transformation

• Add new value to the data--->data provisioning and enrichment

• Manage the data----->security, privacy, discovery, governance

• Productionize data processes---->pipeline monitoring and automation


# data engineering task evolve around ingesting transforming , storage data 

<img width="2056" height="1329" alt="Screenshot 2025-12-04 at 9 54 31 PM" src="https://github.com/user-attachments/assets/8ff4644c-30a8-47cf-81bf-efcb0f4ba2fd" />


# replication and migration serices onboard your data into google cloud 
<img width="1965" height="1119" alt="Screenshot 2025-12-04 at 9 56 24 PM" src="https://github.com/user-attachments/assets/793b8fcf-8b6a-484c-9d31-8e7d7516ed9b" />


# data sources versus data sync 

<img width="1983" height="1103" alt="Screenshot 2025-12-04 at 9 59 23 PM" src="https://github.com/user-attachments/assets/2b352072-33af-497d-a9c1-11969829eeb3" />
-Think of a data source as the starting point of your data journey.It is raw, unprocessed data waiting to be transformed into valuable insights.Any system, application, 
or platform that creates, stores, or shares data can be considered a data source.Two examples of Google Cloud products used in the ingest phase are Cloud storage, a data lake

<img width="1912" height="1102" alt="Screenshot 2025-12-04 at 10 02 38 PM" src="https://github.com/user-attachments/assets/3adda457-022b-4bc3-8b98-69cc01fbd361" />
-join, or customize a data source so that it matches a specific downstream data or reporting requirement.
-There are three main transformation patterns: extract and load, extract, load, and transform, and extract, transform, and load.
-
<img width="1920" height="1071" alt="Screenshot 2025-12-04 at 10 04 10 PM" src="https://github.com/user-attachments/assets/637998e6-72d5-492d-88f1-5525be2e8c80" />
-The store stage of a data pipeline represents the last step when we deposit data in its final form.
-It's where processed and transformed data is stored for future use, analysis, and decision-making.
-Think of it as the reservoir at the end of the river, where valuable information is collected and readily available.
-Two examples of Google Cloud products used in the store phase are BigQuery, a serverless data warehouse, and Bigtable, a highly scalable no SQL database.
