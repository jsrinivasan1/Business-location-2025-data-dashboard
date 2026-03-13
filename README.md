# B-READY 2025 — Business Location Dashboard

Interactive data explorer for the World Bank's Business Ready (B-READY) 2025 Business Location topic, covering **101 economies** and **114 indicators** across three pillars.

## Quick Start

Open `BL_2025_Dashboard.html` in any browser. No server, no install, no dependencies — everything is self-contained in a single HTML file (Chart.js loaded via CDN).

## Features

| Tab | Description |
|-----|-------------|
| **Overview** | Summary cards, score distribution, pillar averages by region and income group, category breakdowns, pillar balance scatter |
| **Rankings** | Sortable table of all economies with inline score bars for BL Overall, Pillars 1–3, and all 10 categories |
| **Indicator Explorer** | Select any of 30 subcategories to see regional and income group breakdowns at both subcategory and individual indicator level |
| **Economy Profile** | Deep dive into a single economy — radar chart vs global mean, global and regional rank, full subcategory breakdown |
| **Compare** | Side-by-side radar comparison of up to 4 economies with detailed category scores |
| **Scatter Plot** | Plot any two metrics (pillars, categories, subcategories) against each other, color-coded by region |

All tabs respond to the **Region**, **Income Group**, and **Search** filters at the top.

## Data

- **Source**: `BLdata2025.xlsx` (B-READY 2025 scored data)
- **Classifications**: Region and income group from `BL_Analysis_2025_by_Income_Region.xlsx`
- **Coverage**: 101 economies, 3 pillars, 10 categories, 30 subcategories, 114 indicators
- **Regions**: East Asia & Pacific, Europe & Central Asia, Latin America & Caribbean, Middle East North Africa & Afghanistan, North America, South Asia, Sub-Saharan Africa
- **Income groups**: Low income, Lower middle income, Upper middle income, High income

## Structure

```
├── BL_2025_Dashboard.html    # Self-contained interactive dashboard
├── BLdata2025.xlsx           # Source data (scored indicators by economy)
├── BL_Analysis_2025_by_Income_Region.xlsx  # Region/income classifications
└── README.md
```
