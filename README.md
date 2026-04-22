# Energy Strategy Decision Support System (ESD-SS)

[](https://www.python.org/)
[](https://plotly.com/)
[](https://www.xjtlu.edu.cn/)

## 📖 Executive Summary

The **Energy Strategy Decision Support System (ESD-SS)** is a high-performance analytical platform engineered for financial analysts, institutional investors, and strategic planners.

By leveraging audited financial data from global energy leaders (including XOM, CVX, BP, and SHEL), the system deconstructs corporate performance through the **DuPont Analysis framework**. It provides a rigorous, multi-dimensional evaluation of capital productivity and operational efficiency across the global energy landscape from **2018 to 2025**.

-----

## ⚡ Technical Advantages & Professional Value

This system is designed to bridge the gap between raw financial data and executive-level strategy:

  * **Integrated Single-View Architecture**: The dashboard utilizes a **Single-Page Application (SPA)** logic. All critical modules—including Profitability Cycles, the DuPont Matrix, and Market Concentration—are housed within a single, responsive interface, allowing for instantaneous data exploration without page reloads.
  * **One-Click Automated Deployment**: Engineered for efficiency, the system features a fully automated workflow. Upon execution, the backend handles complex data cleaning and SIC industry mapping before **automatically launching** the interactive dashboard in your default browser.
  * **High-Performance Interactivity**: Powered by the Plotly engine, the system supports zero-latency filtering and **live ticker searching**. This allows users to pinpoint specific companies and visualize their position against industry benchmarks in real-time.
  * **Sector-Specific Data Rigor**: Built-in logic filters out fiscal anomalies and non-operating distortions, ensuring that metrics like **Asset Turnover** and **Net Margin** reflect the true operational reality of the energy sector.

-----

## 📊 Strategic Analysis Modules

  * **DuPont Dynamic Matrix**: Deconstructs Return on Assets (ROA) to identify strategic drivers:
    $$ROA = \text{Net Margin} \times \text{Asset Turnover}$$
    Distinguishes between **Premium-driven** (High Margin) and **Volume-driven** (High Efficiency) business models.
  * **Market Structure Explorer**: A treemap visualization of revenue concentration. Includes **drill-down functionality** to access detailed SIC industry profiles and HQ locations for each firm.
  * **Operational Benchmarking**: Statistical distributions (Box plots) that locate corporate asset productivity within industry deciles, highlighting "Alpha" opportunities.

-----

## 🚀 Usage Instructions

### Prerequisites

The following Python libraries are required for data processing and visualization:

```bash
pip install pandas plotly
```

### Execution Steps

1.  Ensure the source file `wrds_energy_data.csv` is located in the same directory as the notebook.
2.  Open **`GlobalEnergy.ipynb`** in your preferred environment (Jupyter Notebook, JupyterLab, or VS Code).
3.  **Run All Cells**: The script will process the WRDS dataset, generate a local `index.html` report, and **automatically open the interactive dashboard** in your system's default web browser.

-----

## 📝 Professional Disclosure & Compliance

### Analytical Limitations

  * **Reporting Lag**: Insights are derived from audited annual and quarterly filings (WRDS Compustat), which contain a standard reporting delay and may not capture intraday geopolitical price volatility.
  * **Data Normalization**: Net Margins are capped at $[-50\%, 50\%]$ to ensure that extreme, one-time corporate restructuring events do not skew industry-wide averages.

### Methodology & AI Disclosure

  * **AI Integration**: Generative AI was employed to optimize the frontend Bootstrap UI and refine the JavaScript event listeners for the real-time search functionality.
  * **Originality**: All core financial modeling, data cleaning pipelines, and industry mapping frameworks were independently designed and implemented by the author.

-----

**Author:** Fuhan Liu | **Student ID:** 2468474  
**Project:** ACC102 Mini Assignment - International Business School Suzhou (IBSS)  
**Date:** April 2026
