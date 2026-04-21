# Energy Industry Financial Performance Dashboard (2018-2025)

## Project Overview
This project is an interactive data product designed to analyze the financial health and operational efficiency of major global energy companies (e.g., ExxonMobil, Chevron, BP). By utilizing the DuPont Analysis framework, the tool visualizes key metrics such as **Net Profit Margin**, **Asset Turnover**, and **Return on Assets (ROA)** to provide insights into corporate performance trends over a decade.

This project was developed as part of the **ACC102: Python Data Product** assignment at Xi'an Jiaotong-Liverpool University.

## Key Features
- **Integrated Dashboard**: A high-level overview of industry performance and key rankings.
- **Interactive Profitability Analysis**: Visualizes Net Margin trends with a dynamic year slider.
- **Efficiency Mapping**: Scatters companies based on their Asset Turnover vs. Net Margin to identify business models.
- **Comparative Analysis**: Side-by-side performance comparison for specific industry leaders.
- **Raw Data Explorer**: A searchable and filterable table of the underlying financial dataset.

## Data Source
[cite_start]The analysis is based on financial data retrieved from **WRDS (Wharton Research Data Services)**[cite: 146, 148].
- **Dataset**: `wrds_energy_data.csv`
- **Timeframe**: 2018 – 2025
- **Focus**: Energy sector firms categorized by SIC codes.

## Technical Requirements & Installation
[cite_start]To run the analysis and generate the interactive HTML reports, you need Python 3.x and the following libraries:

```bash
pip install pandas plotly
```
## How to Run
Clone this repository to your local machine.
Ensure the wrds_energy_data.csv file is in the same directory as the script.
Execute the Python notebook Untitled.ipynb.
The script will automatically generate five HTML files representing the product pages:

index.html (Strategic Overview)

trends.html (Profitability Cycles)

analysis.html (DuPont Dynamic Matrix)

market_share.html (Market Landscape)

efficiency.html (Operational Statistics)

## Analytical Insights
The tool identifies whether a company’s ROA is driven primarily by high-profit margins (Profitability-driven) or rapid asset turnover (Efficiency-driven). By deconstructing ROA into these two levers, the product offers a deep dive into the strategic positioning and capital productivity of energy giants across different market cycles.

Developed by: Fuhan Liu

Student ID: 2468474

Submission Date: April 2026
