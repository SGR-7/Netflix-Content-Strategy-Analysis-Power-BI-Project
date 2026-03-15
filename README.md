<p align="center">
  <img src="Netflix%20TV%20Shows%20and%20Movies%20Analysis/assets/logo/Netflix%20Logo.png" alt="Netflix Logo" width="300">
</p>

# Netflix Content Strategy Analysis

## Project Overview
This project provides a comprehensive data-driven analysis of the Netflix library. Using **Power BI**, I transformed raw dataset records into actionable insights regarding content growth, regional distribution, and audience ratings. The analysis focuses on identifying the strategic shift between Movies and TV Shows and how Netflix targets different global markets.

---

## Key Insights
* **Content Type Distribution:** A deep dive into the ratio of Movies vs. TV Shows, revealing a **71% to 29%** split in favor of Movies.
* **Global Reach:** Identification of top-contributing countries, with the **United States**, **India**, and the **United Kingdom** leading content production.
* **Growth Trends:** Visualization of release patterns over time, highlighting a significant surge in content additions starting around 2015.
* **Audience Segmentation:** Breakdown of content by maturity ratings (e.g., TV-MA, TV-14) and top genres to understand Netflix's target demographics.

---

## Tools & Technical Features
* **Power BI Desktop:** Core tool for data visualization and report orchestration.
* **Power Query (ETL):** Performed data cleaning and standardizing date formats.
* **DAX (Data Analysis Expressions):** Developed custom measures for dynamic counts and percentages.
* **Custom Theming:** Implemented a bespoke **Red & Dark theme** (`Red Theme.json`) to align the dashboard with Netflix’s official branding.
* **Geospatial Analysis:** Integrated a custom TopoJSON map (`World Map.json`) for precise geographic data mapping.

---

## Dashboard Preview
The dashboard is designed for high scannability and professional aesthetic, featuring:

* **Executive KPIs:** Total Titles (7,971), Total Ratings, and Genres at a glance.
* **Interactive Slicers:** Filter by Show Type, Release Year, and Country.
* **Visual Mix:** A combination of Column charts, Donut charts for distribution and Area charts for trends.

---

## Project Files
| File Name | Description |
| :--- | :--- |
| **Netflix TV Shows and Movies Analysis.pbix** | The complete, interactive Power BI report file. |
| **dashboard.pdf** | A portable, high-quality export of the final dashboard view. |
| **Netflix TV Shows and Movies.csv** | The source dataset containing over 8,000 records. |
| **Red Theme.json** | The custom JSON configuration for the "Netflix-style" visual theme. |
| **World Map.json** | The custom map file used for geographic visualizations. |
| **Netflix Logo.png** | Branding asset used for dashboard headers. |
| **dashboard.png** | High-resolution screenshot for quick repository previews. |

---

## How to Use
1.  **Clone the Repository:** Download all files to a local directory.
2.  **Open the Report:** Launch `Netflix TV Shows and Movies Analysis.pbix` using Power BI Desktop.
3.  **Data Refresh:** If the data path changes, point the data source to the `Netflix TV Shows and Movies.csv` file via **Transform Data > Data Source Settings**.
4.  **Customization:** You can apply the `Red Theme.json` to other reports by going to the **View** tab > **Themes** dropdown > **Browse for themes**.