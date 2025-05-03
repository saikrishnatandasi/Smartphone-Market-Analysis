# Smartphone Market Analysis Dashboard 📊



## Project Overview 🔍

This repository contains a comprehensive Power BI dashboard analyzing global smartphone market trends. The project transforms raw data into actionable insights through interactive visualizations across multiple dimensions including technical specifications, pricing strategies, and market competition.

## Data Source 📥

- **Source**: Kaggle smartphone market dataset
- **Coverage**: Global markets (India, USA, China, Dubai)
- **Timeframe**: 2014-2025
- **Data Points**: 904 smartphone models across 17+ manufacturers

## Data Processing Methodology 🛠️

1. **Data Extraction**: Downloaded raw dataset from Kaggle
2. **Data Cleaning & Transformation**:
   - Standardized company names and model identifiers
   - Handled missing values using appropriate techniques
   - Created consistent formatting across currency and specification fields
   - Used Power Query for all transformation operations
3. **Data Modeling**:
   - Created relationships between dimension tables (manufacturers, regions) and fact tables
   - Built date hierarchy for time-based analysis
4. **DAX Implementation**:
   - Created calculated measures for KPIs
   - Developed complex calculations for market share analysis
   - Implemented filters and slicers for interactivity

## Dashboard Structure 📈

The dashboard consists of three main pages:

### 1. Overview
- Market-wide KPIs (Total Models, Average Price, RAM Distribution)
- Models by Company visualization
- Mobile Releases by Year trend analysis
- Average Price comparison by manufacturer

### 2. Price Analysis
- Average pricing across different markets (India, USA, China, Dubai)
- Price trends over time (2014-2025)
- Regional price comparison by manufacturer

### 3. Technical Specs
- RAM category distribution
- Screen size vs Battery capacity analysis
- Processor distribution analysis
- Technical score computation based on key specifications

## Key Insights 💡

- The 4GB-8GB RAM segment dominates at 55.29% market share, while 12GB+ represents only 3.35% of models
- MediaTek leads processor adoption with 289 models, followed by Snapdragon (247) and Qualcomm (121)
- Average smartphone prices in India rose from ₹14K in 2014 to ₹50.46K in 2025, with premium brands (Huawei, Apple) commanding over ₹100K
- Screen size vs. battery capacity analysis reveals Samsung prioritizes larger batteries, while Apple focuses on display quality
- Oppo leads with most models (129), though Apple (97) maintains higher price positioning across all markets

## Technologies Used 💻

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel (initial data inspection)

## How to Use 🚀

1. Clone this repository
2. Download [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Open the .pbix file in Power BI Desktop
4. Interact with the dashboard by using the filters and slicers

## Future Enhancements 🔮

- Add forecasting models for price trends
- Include additional technical specifications (camera quality, storage options)
- Incorporate customer satisfaction data
- Add competitor analysis dashboard



## License 📄

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments 🙏

- Data sourced from Kaggle community
- Inspiration from various smartphone market reports
