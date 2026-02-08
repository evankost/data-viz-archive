# Data Viz Archive

This repository contains a collection of interactive projects focusing on road safety analytics and global socioeconomic trends. It includes custom JavaScript (D3.js) dashboards and a separate set of Tableau BI dashboards.

## Project Links

### Road Safety and Helmet Usage

* **Greece Map**: [View Live Dashboard](https://evankost.github.io/data-viz-archive/road-accidents-safety/d3-map/index.html)
* **Tableau BI Dashboards**: [View All on Tableau Public](https://public.tableau.com/app/profile/evangelos.kostoulas)

### PISA Global Analysis

* **Main Dashboard**: [View Live Dashboard](https://evankost.github.io/data-viz-archive/pisa-global-analysis/index.html)
* **Regional Trends**: [View Dashboard One](https://evankost.github.io/data-viz-archive/pisa-global-analysis/dashboardOne.html)
* **Resource Allocation**: [View Dashboard Two](https://evankost.github.io/data-viz-archive/pisa-global-analysis/dashboardTwo.html)
* **PISA Economy (Group Project)**: [evankos.netlify.app](https://evankos.netlify.app/)

---

## Project Descriptions

### 1. Road Safety and Helmet Usage

  A study on road mortality and the impact of safety equipment for two-wheeled vehicles.

* **D3.js Greek Map**: Features a geospatial analysis of Greece with the ability to toggle between Municipalities and Regional Units.

* **Tableau BI Suite**: Includes a 15-year trend analysis of EU mortality rates (2007-2022) and a detailed breakdown of Greek accident data (2016-2022).

* **Data Pipeline**: Utilizes Tableau Prep for ETL, merging datasets from ELSTAT, EUROSTAT, and the WHO.

### 2. PISA Global Education Analysis

   An exploration of how national wealth and education expenditure correlate with student performance.

* **Interactive Metrics**: Synchronized charts comparing Math, Reading, and Science scores from the 2022 PISA results.
* **Economic Correlation**: Links academic performance to World Bank GDP data and UNESCO education spending.
* **Resource Analysis**: Visualizes school-level factors such as teacher certification and staff shortages.

---

## Technical Stack

* **Languages**: JavaScript (D3.js), HTML5, CSS3.
* **BI Tools**: Tableau Desktop, Tableau Prep Builder.
* **Data Processing**: ETL pipelines for .csv, .xlsx, and .hyper formats.
* **Geospatial**: GeoJSON mapping and hex-binning.
---

## Repository Structure

```text
Data-Viz-Archive/
├── pisa-global-analysis/          # D3.js project for PISA 2022 trends
│   ├── data/                      # Pisa_Economy_Final.csv
│   ├── dashboardOne.html
│   ├── dashboardTwo.html
│   └── index.html
├── road-accidents-safety/
│   ├── d3-map/                    # Custom Greek hex-map and charts
│   │   ├── data/                  # GeoJSON and mortality CSVs
│   │   ├── images/                # favicon.ico
│   │   ├── index.html
│   │   ├── scripts.js
│   │   └── styles.css
│   └── tableau-dashboards/        # Tableau workbooks and Prep flows
│       ├── data-sources/          # Raw CSVs, .tfl flows, and .hyper extracts
│       ├── screenshots/           # Dashboard previews
│       └── README.md
└── README.md                      # Main project documentation
```

---

## Credits and Data Sources

* **WHO**: Global mortality indicators.

* **ELSTAT**: Hellenic Statistical Authority road accident data.

* **EUROSTAT**: European road safety and population statistics.

* **OECD/PISA**: International student assessment results.

* **World Bank**: National GDP and economic indicators.

* **NRSO**: National Technical University of Athens Road Safety Observatory.

---

## License

This project is licensed under the MIT License.