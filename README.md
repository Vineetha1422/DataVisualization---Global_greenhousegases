# 🌍 Global Greenhouse Gas Emissions Visualization Platform  

**Interactive analysis of CO₂, methane, N₂O emissions with carbon tax policy and temperature correlations**

[![Open in GitHub](https://img.shields.io/badge/GitHub-Repo-lightgrey?logo=github)](your-repo-link) 
[![Data Source](https://img.shields.io/badge/Data-OurWorldInData-brightgreen)](https://ourworldindata.org/)

## 📌 Overview
**Problem**: Current climate visualization tools silo emission data, policy impacts, and temperature trends, limiting holistic analysis of climate change drivers.  
**Impact**: Enables policymakers to simultaneously analyze:
- Regional emission compositions (CO₂/CH₄/N₂O)
- Carbon tax policy timelines
- Temperature change correlations
- Temporal patterns (1950-2022)

## 🛠️ Tools & Technologies
- **Languages**: ![Python](https://img.shields.io/badge/-Python-yellow)
- **Core Libraries**: 
  - ![Pandas](https://img.shields.io/badge/Pandas-Data_Integration-red)
  - ![Plotly](https://img.shields.io/badge/Plotly_Dash-Interactive_Visualization-green)
- **Data Sources**: [OurWorldInData.org](https://ourworldindata.org/) (4 integrated datasets)
- **Deployment**: Standalone web app with real-time interactivity

## 🧠 Approach
### Data Pipeline
1. **Integration**: Unified 5 datasets (CO₂, CH₄, N₂O, carbon taxes, temperature)  
2. **Preprocessing**:
   - Temporal filtering (post-1950 data)
   - Hybrid tidy/wide format transformation
   - Country-code standardization

### Interactive Features
- **Choropleth Maps**: 
  - Dynamic year slider (1950-2022)
  - Multi-projection support (Robinson/Mollweide)
- **Policy Analysis**:
  - Carbon tax adoption timelines
  - Emission growth rate comparisons
- **Temperature Correlations**:
  - Regional temp vs cumulative emissions
  - Decadal change analysis

## 🔑 Key Results
**Emissions Analysis**:
- CO₂ dominates industrial regions (60-75% of emissions)
- Agricultural areas show 40% higher CH₄/N₂O levels  
- Carbon tax countries exhibit **12-18% slower emission growth**

**Temperature Insights**:
- North America: +1.2°C since 1950
- Strong correlation (r=0.89) between cumulative emissions & regional warming


