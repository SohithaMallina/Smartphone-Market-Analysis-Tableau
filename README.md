# Global Smartphone Market Analysis 2025

**Master's Data Visualization Final Individual Project | December 2025**

An interactive Tableau data visualization project analyzing the **2025 global smartphone market** using a dataset of **1,000 smartphone records across 15 attributes**. The project explores smartphone pricing, hardware specifications, user ratings, operating systems, and release trends through six analytical worksheets, three dashboards, and a Tableau story.

> **Academic Context:** Completed as my Master's Data Visualization final individual project in December 2025. I earned an **A grade in the Data Visualization course**.

---

## Project Overview

The global smartphone market is shaped by rapid technological change, varying consumer preferences, and strong competition among manufacturers. This project was developed to explore how smartphone specifications and market characteristics relate to pricing, ratings, platform differences, and release trends.

The analysis focuses on questions such as:

- How does average smartphone pricing vary across brands?
- How are RAM and storage related to smartphone price?
- How do camera and battery specifications compare across brands?
- What relationship exists between price and user rating?
- How do Android and iOS devices compare across major hardware features?
- How do smartphone specifications vary across release months?

The goal was to transform raw smartphone data into clear, interactive visualizations that support comparative analysis and data-driven interpretation.

---

## Dataset

- **Dataset:** World Smartphone Market 2025
- **Source:** Kaggle
- **Provider:** `shahzadi786`
- **Records:** 1,000
- **Columns:** 15
- **Domain:** Mobile Technology / Consumer Electronics
- **Dataset Link:** https://www.kaggle.com/datasets/shahzadi786/world-smartphone-market-2025

### Dataset Fields

| Field | Description |
|---|---|
| `brand` | Smartphone manufacturer |
| `model` | Smartphone model |
| `price_usd` | Price in U.S. dollars |
| `ram_gb` | RAM capacity in GB |
| `storage_gb` | Internal storage in GB |
| `camera_mp` | Camera resolution in megapixels |
| `battery_mah` | Battery capacity in mAh |
| `display_size_inch` | Display size in inches |
| `charging_watt` | Charging power in watts |
| `5g_support` | 5G support status |
| `os` | Operating system |
| `processor` | Processor type |
| `rating` | User rating |
| `release_month` | Release month |
| `year` | Release year |

---

## Tools & Technologies

- **Tableau Desktop** — data visualization, interactive worksheets, dashboards, filters, trend analysis, and story creation
- **Microsoft Excel** — data cleaning, validation, formatting, and preliminary data inspection
- **GitHub** — project documentation and portfolio presentation

---

## Data Cleaning

The dataset was prepared in Microsoft Excel before visualization in Tableau.

Key cleaning steps included:

1. Checked for duplicate records.
2. Trimmed leading and trailing spaces in text fields.
3. Standardized the `5g_support` field to consistent **Yes/No** values.
4. Converted numerical fields to appropriate numeric formats.
5. Checked for invalid values such as zero or negative prices and RAM values.
6. Reviewed critical fields for missing values.
7. Standardized categorical values for consistent grouping and analysis in Tableau.

---

## Tableau Analysis

The workbook contains **six analytical worksheets**.

### 1. Price Distribution by Brand

Compares average smartphone prices across brands to examine pricing differences and overall brand positioning.

### 2. RAM vs Storage vs Price

Explores the relationship between RAM, storage capacity, and smartphone price using a scatter-based visualization.

### 3. Camera & Battery Comparison

Compares camera resolution and battery capacity across smartphone brands to highlight hardware differences.

### 4. Price vs Rating

Analyzes the relationship between smartphone price and user rating at the individual model level.

### 5. OS Feature Comparison

Compares Android and iOS devices across major specifications including RAM, storage, battery capacity, camera capability, and charging power.

### 6. Release Trends

Uses a heatmap-style visualization to examine how smartphone specifications vary across release months.

---

## Dashboard Preview

### Dashboard 1 — Brand Pricing Overview

Combines brand-level pricing analysis with camera and battery comparisons to provide a high-level view of smartphone brand positioning.

![Brand Pricing Overview](images/brand_pricing_overview.png)

---

### Dashboard 2 — Specs & Price Relationships

Brings together RAM, storage, price, and rating analysis with interactive filters to explore specification and pricing relationships at the model level.

![Specs & Price Relationships](images/specs_price_relationships.png)

---

### Dashboard 3 — Release Trends

Combines release-month trends with operating-system feature comparisons to highlight changes in smartphone specifications and platform differences.

![Release Trends](images/release_trends.png)

---

## Tableau Story

The workbook also includes **Smartphone Market Story 2025**, a multi-step Tableau story that connects the individual analyses into a structured narrative covering:

- Market overview
- Brand pricing
- RAM and storage relationships
- Camera and battery comparisons
- Price and rating analysis
- Operating-system comparisons
- Release trends
- Final conclusions

The story was designed to move from broad market comparisons to more detailed specification-level analysis and summarize the overall findings in a presentation-style format.

---

## Key Findings

The analysis highlights several market-level patterns:

- Smartphone brands show different pricing and product-positioning patterns.
- RAM and storage are useful dimensions for comparing smartphone pricing and configurations.
- Camera and battery specifications vary across manufacturers.
- Price and user rating do not move uniformly across every smartphone model, making model-level comparison important.
- Android devices show broader hardware configuration diversity, while iOS represents a more standardized product ecosystem within the dataset.
- Smartphone specifications and release activity vary across months, supporting analysis of product-release patterns.

---

## Repository Structure

```text
Smartphone-Market-Analysis-Tableau/
│
├── README.md
│
├── data/
│   └── Smartphone_Market_Cleaned.xlsx
│
├── documentation/
│   └── Smartphone_Market_Analysis_Report.docx
│
├── images/
│   ├── brand_pricing_overview.png
│   ├── specs_price_relationships.png
│   └── release_trends.png
│
└── tableau/
    └── Smartphone_Market_Analysis_2025.twbx
```

> File names in the repository may vary slightly if the original project file names were preserved.

---

## How to View the Tableau Project

1. Download the `.twbx` file from the `tableau/` folder.
2. Open it using **Tableau Desktop**.
3. Navigate through the six worksheets, three dashboards, and the **Smartphone Market Story 2025** tab.
4. Use the available filters to explore brands, models, operating systems, and release months.

The packaged Tableau workbook allows the project to be opened as a complete Tableau file with its associated project data.

---

## Skills Demonstrated

- Tableau
- Microsoft Excel
- Data Cleaning
- Data Preparation
- Data Visualization
- Dashboard Development
- Exploratory Data Analysis
- Comparative Analysis
- Trend Analysis
- Scatter Plots
- Dual-Axis Visualizations
- Heatmaps
- Interactive Filters
- Tableau Stories
- Data Storytelling

---

## Academic Context

- **Program:** Master's Degree
- **Course:** Data Visualization
- **Project Type:** Final Individual Project
- **Completed:** December 2025
- **Course Grade:** **A**

---

## Author

**Sohitha Mallina**

This repository is part of my data analytics and business analysis portfolio and demonstrates my ability to clean data, build interactive Tableau visualizations, develop dashboards, and communicate findings through data storytelling.
