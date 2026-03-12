# Agri-Merchandising Analytics Hub
**Candidate:** Mohammed Idris Berick | Durham University (Economics)

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://merchandising-trainee-portfolio-moberick.streamlit.app)

**🔗 [Live Interactive Dashboard](https://merchandising-trainee-portfolio-moberick.streamlit.app)**

## Executive Summary
[cite_start]This hub bridges the gap between academic theory and practical trading[cite: 14]. [cite_start]It automates the mapping of physical flows for grains and oilseeds to identify market tightness—demonstrating the quantitative risk analysis and commercial negotiation skills required for Cargill's Ag & Trading enterprise[cite: 10, 11].

## Key Features
* [cite_start]**Data Pipeline Automation (`data_pipeline.py`)**: Automates aggregation of physical inventory and paper hedges to generate daily 'Net Flat Price Exposure'[cite: 15, 37]. 
* **Merchandising Analytics Engine (`analytics_engine.py`)**: 
    - [cite_start]**Balance Sheet Construction**: Calculates Ending Stocks and Stocks-to-Use Ratios using the core balance equation[cite: 43].
    - **Market Tightness Logic**: Automatically flags supply bottlenecks (e.g., the 7.04% Stocks-to-Use ratio identified for 2025 Corn).
    - [cite_start]**MTM Variance Isolation**: Separates key drivers like Price Delta and FX fluctuations[cite: 15, 38].
* **Interactive Dashboard (`app.py`)**: A Streamlit UI providing desk-ready insights on margins and supply bottlenecks[cite: 43].

## Commercial Context
This project mirrors the daily accountabilities of a merchandising desk, focusing on the relationship between supply/demand fundamentals and price momentum[cite: 13, 16]. It leverages my experience in supply chain consulting and commercial execution to deliver actionable strategies[cite: 17, 18, 50, 53].

## Setup & Usage
1. Install dependencies: `pip install -r requirements.txt`
2. Generate data: `python data_pipeline.py`
3. Launch dashboard: `streamlit run app.py`
