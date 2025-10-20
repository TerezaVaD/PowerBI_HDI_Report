# Power BI Report – Human Development and Economy

## Overview
This Power BI report provides an interactive overview of countries’ socio-economic and human development indicators. The report includes **three pages**:  

1. **Overview** – Basic socio-economic indicators such as population, GDP per capita, and literacy rate. Includes a map, cards, and interactive slicers for region and population size.  
2. **Economy** – Focuses on GDP and GNI per capita, allowing comparison between countries and regions using stacked column charts, pie charts, and tables.  
3. **Living Standards** – Analyzes Human Development Index (HDI), life expectancy, education, and the relationship between education and GDP using bubble charts, stacked column charts, and cards.  

---

## Data Sources
- [United Nations Development Programme – Human Development Reports](https://hdr.undp.org/)  

---

## Features
- **Interactive slicers** for region, population, and HDI values.  
- **Multiple visual types**:  
  - Cards  
  - Maps  
  - Bubble Charts  
  - Stacked Column Charts  
  - Pie Charts  
  - Tables  
- **Measures and calculated columns**:  
  - **HDI / GNI Ratio** (measure)  
  - **Education / GDP Ratio** (calculated column)  
- **Tooltips** provide clear interpretation of all metrics.    
- **Navigation between pages** and clickable links to sources.  

---

## Notes
- All values are standardized and formatted for readability (e.g., population with thousand separators, HDI with two decimals).  
- The report uses long-format transformation (Attribute / Value) for comparing multiple metrics in one visual.  
- The report is fully interactive when opened in **Power BI Desktop** or **Power BI Service**.  

---

## Files
- `Human_Development_Report.pbix` – Power BI report file
