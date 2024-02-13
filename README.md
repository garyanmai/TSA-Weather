# Analyzing TSA Throughput Data and Historical Weather Information
- A Data Warehousing for Analytics student group project for CIS 4400 course.

# Group Members:
- Andy Chen
- Gar Yan Mai (Carmen)
- Tenzin Pelchok

**Requirements**: https://docs.google.com/document/d/1djD0VMOxct1eiHj7tiv0HYmfNdgD4YXA1nGX4urJj_U/edit?usp=sharing

**Link to TSA Data Set**: https://www.tsa.gov/foia/readingroom?page=1

**Link to Weather API Data Set**: https://open-meteo.com/en/docs/historical-weather-api

**Data Dictionary**: https://docs.google.com/spreadsheets/d/1IMv8EoMX21I7BfsayR2Qs0bNYVQoMm-qADgmQC2n_Bk/edit?usp=sharing

**Data Model**: ![SAve](https://github.com/TENPEL08/CIS4400/assets/74534392/23ee5fc3-0690-483d-8d9b-cf12250e26ef)

**Presentation**: https://docs.google.com/presentation/d/1EuS2QrsZNMp_pGg0LIwexvZJP1ALPeWN-lgObN8_OzY/edit?usp=sharing

**Data Visualization Dashboard**: https://lookerstudio.google.com/reporting/bbf45feb-7196-41bb-9c50-110a8b7ddeee

**Final Dashboard**:

<img width="794" alt="Screenshot 2023-12-07 at 3 25 04 AM" src="https://github.com/TENPEL08/CIS4400/assets/145724601/d51ce18f-9030-4170-be20-30328285cfc4">


**Cloud Service**: Azure Storage Service, Azure Blob, Google BigQuery, Google Cloud Storage, Google Looker Studio

**Python Libraries Needed**: pdfplumber, pandas, os, azure-storage-blob, azure.storage.blob,geopy, openmetro_requests, requests_cache, retry_requests, geopy, 


Steps:
1. **Data-ETL**: Extract, clean, transform, and load the data to a cloud storage service. (data-extract-transform-load_script)
4. **Data-Warehouse**: Design The Data Model, Create Script for Data Warehouse, Load Data into Data Warehouse (dataWarehousingScript_groupProject)
5. **Data-Analytics**: Load cleaned data set from Google BigQuery to LookerStudio to create Final Dashboard

