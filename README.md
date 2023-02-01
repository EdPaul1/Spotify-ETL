# Spotify Data ETL
## Architecture
![Spotify](https://user-images.githubusercontent.com/102229086/216042340-fdff3198-a801-40cd-bf1f-7fa0e2c0e01a.JPG)

## Technologies
* Spotify Api - Source of Data.
* Apache Airflow - Workflow Orchestration.
* SQLite - Database
* Apache Airflow is run on Docker
* Tableau For Visualization

## Brief Summary of the project
Recent Playlist on Spotify is loaded to SQLite database using the [Spotify API](https://developer.spotify.com/console/get-recently-played/).Apache Airflow manages the data pipeline.

## Sample Tableau Dashboard

![Capture](https://user-images.githubusercontent.com/102229086/216045402-92ad212b-90be-4196-9637-57204d851126.JPG)
