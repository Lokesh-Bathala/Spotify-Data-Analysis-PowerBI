# Spotify Data Analysis

## Project Overview

This project showcases an in-depth analysis and visualization of personal Spotify listening history data. Leveraging a robust data pipeline, from initial data preparation to interactive dashboard creation in Power BI, this project uncovers fascinating insights into music preferences, listening trends, and top artists over time.

This personal project demonstrates strong capabilities in end-to-end data analytics, including data engineering principles, data modeling, and business intelligence visualization.

## Live Dashboard

Explore the interactive Power BI dashboard directly:
(https://app.powerbi.com/groups/me/reports/3b877b1f-8512-4dcc-a70e-8ceda423865e/d238a67721db3432d8bc?experience=power-bi)

## Key Features of the Dashboard

* **Dynamic Trend Analysis:** Visualize listening activity patterns over days, weeks, and months.
* **Top Artists & Tracks:** Identify most-listened artists and songs, providing insights into popular choices.
* **Genre Exploration:** Understand preferred genres and their evolution.
* **Listening Habits Breakdown:** Discover peak listening times and duration.
* **Interactive Filters:** Drill down into specific periods, artists, or tracks for detailed analysis.

## Technologies Used

* **Python:** Utilized for data cleaning and preprocessing (even though scripts aren't included in the repo, it's vital to mention the skill used for data preparation).
* **SQL:** Employed for data transformation and ensuring data integrity (similarly, to highlight the skill applied to the data).
* **Power BI Desktop:** Used for data modeling (creating relationships, defining measures), DAX formula creation, and designing interactive dashboards.
* **Power BI Service:** For publishing and sharing the interactive report online.
* **CSV (spotify_history.xlsx - Sheet1.csv):** The primary data source, representing exported Spotify listening history.

## Data Source

The core dataset for this project is `spotify_history.xlsx - Sheet1.csv`, which contains personal streaming data exported from Spotify. The data typically includes information such as track name, artist, album, play duration, and timestamp.

## Project Structure

* `spotify_history.xlsx - Sheet1.csv`: The cleaned and prepared data file used for the Power BI report.
* `Spotify_Data_Analysis.pbix`: The Power BI Desktop file containing the complete data model, queries, and dashboard design.
* `screenshots/`: Directory containing visual screenshots of the dashboards.
* `README.md`: This file.

## How to Set Up and View Locally

To explore the project locally:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/LokeshBathala/Spotify-Data-Analysis.git](https://github.com/LokeshBathala/Spotify-Data-Analysis.git)
    cd Spotify-Data-Analysis
    ```
2.  **Open in Power BI Desktop:**
    * Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
    * Open the `Spotify_Data_Analysis.pbix` file using Power BI Desktop.
    * The dashboards will load, and you can interact with them. You may need to refresh the data source and point it to the local `spotify_history.xlsx - Sheet1.csv` file if Power BI can't locate it automatically.

## Author

**Lokesh Bathala**
* [LinkedIn](https://www.linkedin.com/in/lokesh-bathala) - 
* [GitHub](https://github.com/LokeshBathala) 

---
