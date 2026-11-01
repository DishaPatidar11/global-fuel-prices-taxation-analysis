# global-fuel-prices-taxation-analysis
An interactive Tableau data analytics project exploring global fuel prices, taxation policies, subsidies, and economic trends from 2020–2026, presented through dashboards and a web-based interface.
# Global Fuel Prices and Taxation Analysis (2020–2026)

## 1. Project Overview

This project analyses global fuel prices, taxation, subsidies, and economic development trends using Tableau Public. It explores how petrol, diesel, and LPG prices vary across countries and regions, and how taxation, subsidies, and crude oil prices relate to these variations.

The project transforms a global fuel-price dataset into interactive dashboards designed to support data exploration, comparative policy analysis, and supply-chain planning.

### Live Project Demonstration

**Project Website:**  
https://global-fuel-prices-taxation-analysis.onrender.com/

Visit the live website to explore the project overview and access the embedded Tableau dashboard.

### Interactive Tableau Dashboard

**Tableau Public — Complete Project Story:**  
https://public.tableau.com/app/profile/disha.patidar7671/viz/GlobalFuelPricesandTaxationAnalysis2020-2026/STORY

Open the Tableau Public Story to explore the project's three scenario-based dashboards.

### Source Code and Documentation

**GitHub Repository:**  
https://github.com/DishaPatidar11/global-fuel-prices-taxation-analysis

The repository contains project documentation, dataset files, Tableau project resources, and supporting website files.

---

## 2. Project Objectives

The primary objectives of this project are:

- Analyse global petrol, diesel, and LPG price variations.
- Explore the relationship between fuel prices and taxation.
- Examine the role of fuel subsidies across different countries.
- Compare fuel-price trends across geographical regions and income levels.
- Explore how crude oil prices relate to retail fuel prices.
- Present analytical findings through interactive Tableau dashboards.
- Develop practical data-analysis and visualisation skills using Tableau Public.

---

## 3. Tools and Technologies

The project uses the following tools and technologies:

- **Tableau Public:** Data visualisation, dashboard development, and interactive analysis.
- **CSV Dataset:** Source data for the fuel-price and taxation analysis.
- **GitHub:** Project documentation, dataset organisation, and version-controlled project files.
- **Flask:** Website framework used for the project's web interface.
- **Render:** Hosting platform used to publish the project website.

---

## 4. Dataset Overview

The dataset contains approximately **27,468 records** covering **84 countries and 7 geographical regions**, from January 2020 to April 2026.

The dataset supports comparisons of fuel prices, taxation, subsidy levels, and economic categories across countries and over time.

### Key Dataset Fields

- `date` — Date of the recorded observation.
- `country` — Country associated with the observation.
- `region` — Geographical region.
- `income_level` — Income classification of the country.
- `subsidy_level` — Fuel subsidy classification.
- `petrol_usd_liter` — Petrol price in USD per litre.
- `diesel_usd_liter` — Diesel price in USD per litre.
- `lpg_usd_liter` — LPG price in USD per litre.
- `brent_crude_usd` — Brent crude oil price.
- `tax_percentage` — Fuel taxation percentage.

The dataset is stored in the `data/` directory.

---

## 5. Interactive Dashboards

The Tableau project contains three analytical dashboards designed to address different questions about global fuel prices and taxation.

### Dashboard 1: Fuel Taxation and Subsidy Policy

This dashboard explores fuel taxation, subsidy policies, and differences in fuel prices across countries.

It supports comparisons of taxation levels, regional petrol prices, taxation-versus-price patterns, and subsidy-level differences.

**Key focus areas:**
- Fuel taxation comparisons.
- Regional petrol-price differences.
- Taxation and fuel-price relationships.
- Subsidy-level comparisons.

### Dashboard 2: Global Fuel Prices and Supply Chain Planning

This dashboard examines fuel-price variations and trends to support supply-chain planning and comparative analysis.

It helps users compare fuel prices across countries and regions and explore changes in crude oil and retail fuel prices over time.

**Key focus areas:**
- Countries with relatively high and low petrol prices.
- Regional fuel-price comparisons.
- Brent crude oil and fuel-price trends.
- Visual legends and regional comparisons.

### Dashboard 3: Fuel Prices, Taxation and Economic Development

This dashboard explores fuel prices, taxation, and country-level economic categories.

It enables comparisons across income levels and supports exploration of how fuel prices and taxation vary between different groups of countries.

**Key focus areas:**
- Fuel-price comparisons across income levels.
- Taxation comparisons.
- Regional differences.
- Available filters for income level, region, and subsidy level.

### Supporting Worksheet

The project also includes a supporting petrol-price trend visualisation, where available in the published workbook, to help examine changes in petrol prices over time.

---

## 6. View the Interactive Tableau Project

Explore the complete project through the following links.

### Project Website

https://global-fuel-prices-taxation-analysis.onrender.com/

### Tableau Public Story — All Three Dashboards

https://public.tableau.com/app/profile/disha.patidar7671/viz/GlobalFuelPricesandTaxationAnalysis2020-2026/STORY

### GitHub Repository

https://github.com/DishaPatidar11/global-fuel-prices-taxation-analysis

The Tableau Public Story link is provided as the main dashboard link so visitors can navigate the complete project rather than opening only one individual chart.

---

## 7. Repository Structure

The repository is organised into separate project phases, a dashboard-preview folder, the source dataset, and supporting project files.

```text
global-fuel-prices-taxation-analysis/
│
├── 01_Ideation_Phase/
│   └── Ideation and problem discovery
│
├── 02_Requirement_Analysis/
│   └── Project requirements and problem definition
│
├── 03_Project_Design_Phase/
│   └── Architecture, technology, and dashboard design
│
├── 04_Project_Planning_Phase/
│   └── Project planning and communication
│
├── 05_Project_Development_Phase/
│   └── Dashboard development documentation
│
├── 06_Performance_Testing/
│   └── Testing and validation documentation
│
├── 07_Project_Documentation/
│   └── Final project report and future scope
│
├── 08_Project_Demonstration/
│   └── Demonstration planning and supporting documentation
│
├── 09_Dashboard_Previews/
│   └── Dashboard screenshots and previews
│
├── data/
│   ├── global_fuel_prices_Dataset.csv
│   └── README.md
│
├── Tableau Project/
│   └── Tableau workbook and related project resources
│
├── web_integration/
│   └── Supporting website files
│
└── README.md
```

*Note: The structure above is illustrative. Keep the folder and file names consistent with the actual contents of the GitHub repository.*

---

## 8. Project Limitations

- The analysis is based on the supplied dataset and the fields available within it.
- The findings represent patterns and relationships in the data; they do not independently establish causation.
- The analysis is limited to the countries, regions, variables, and date range represented in the dataset.
- The project uses Tableau Public and a CSV dataset for analysis. A separate automated ETL pipeline, live data feed, or database backend is not part of the documented implementation.
- The availability and behaviour of interactive features depend on the published Tableau workbook and its configuration.

These limitations should be considered when interpreting dashboard results or using them for further analysis.

---

## 9. Future Enhancements

Potential future improvements include:

- Integrating regularly updated fuel-price data.
- Automating data preparation and refresh workflows.
- Adding further economic indicators for broader comparisons.
- Expanding cross-country and regional analysis.
- Developing additional analytical views as new data becomes available.
- Improving dashboard usability and accessibility.
- Conducting structured performance and usability testing.

These are proposed enhancements and do not imply that the features have already been implemented.

---

## 10. Author

**Disha Patidar**  
Bachelor of Computer Applications (BCA)  
Second Year — 3rd Semester  
MEDI-CAPS University

**Project Title:** Global Fuel Prices and Taxation Analysis (2020–2026)

**Project Type:** Individual Project

This project was developed for academic skill development and to learn the concepts of Tableau and data analytics.
