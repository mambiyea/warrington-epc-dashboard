# warrington-epc-dashboard
Power BI dashboard analyzing energy efficiency across 94,990 Warrington properties using UK Government EPC data.
# Warrington Energy Performance Certificate Dashboard

**Tool:** Power BI Desktop  
**Data Source:** UK Government EPC Register  
**Region:** Warrington, England  
**Total Properties Analyzed:** 94,990  
**Prepared by:** Mambiyea Kapee  
**Credential:** Diploma of Advanced Studies | Information Technology: Business & Advanced Analytics  
**Institution:** New Brunswick Community College (NBCC), Saint John, NB  

---

## Project Overview

This Power BI dashboard analyzes energy efficiency across 94,990 residential properties in Warrington, England using publicly available Energy Performance Certificate (EPC) data from the UK Government.

The central analytical question driving this project:

> **Which properties in Warrington are most at risk of fuel poverty, and where should retrofit funding be prioritized?**

---

## Tools & Techniques

- Power BI Desktop
- Power Query (data cleaning and transformation)
- DAX (calculated measures)
- Star Schema data modeling (Fact + 5 Dimension tables)

---

## Data Model

Star schema with the following tables:

| Table | Type | Description |
|-------|------|-------------|
| Fact_EPC | Fact | Core property energy data |
| Dim_EnergyRating | Dimension | EPC rating A-G |
| Dim_ConstructionAge | Dimension | Property age bands |
| Dim_PropertyType | Dimension | Flat vs House |
| Dim_BuiltForm | Dimension | Detached, Semi-Detached, Terraced etc |
| Dim_Fuel | Dimension | Heating fuel type |

---

## DAX Measures

- Total Properties
- Avg Energy Score
- % Rated D or Below
- % High Efficiency
- % Low Efficiency
- Avg Heating Cost
- Avg CO2 Emission
- Most Common Rating

---

## Dashboard Pages

1. **Cover Page** — Project title, credentials, navigation buttons
2. **Executive Summary** — 4 KPI cards, overall EPC rating distribution, key findings
3. **Data Overview** — High-level summary of all 94,990 properties
4. **Energy by Property Type** — Flat vs House energy performance comparison
5. **Energy by Construction Age** — How property age affects energy efficiency
6. **Energy by Built Form** — Detached, Semi-Detached, Terraced performance analysis
7. **Energy by Fuel Type** — Impact of heating fuel on energy ratings
8. **Key Insights & Recommendations** — Actionable findings for retrofit prioritization

---

## Key Findings

- **52%** of Warrington properties are rated D or below
- **D** is the most common EPC rating across all property types
- **Pre-1900 properties** have the highest percentage rated D or below
- **Semi-Detached properties** represent the largest share of inefficient housing stock
- **Oil and coal-heated properties** consistently underperform compared to mains gas
- **Newer builds (2007 onwards)** achieve the highest energy efficiency scores

---

## Recommendations

1. **Prioritize retrofit programmes** for pre-1900 properties — insulation upgrades and modern heating systems would have the highest impact on Warrington's overall EPC ratings
2. **Accelerate fuel switching** from oil and coal to mains gas or heat pumps in Semi-Detached and older terraced properties to achieve the greatest efficiency gains across the borough

---

## Screenshots

### Cover Page
![Cover Page](screenshots/Cover%20Page.jpg)

### Executive Summary
![Executive Summary](screenshots/Executive%20Summary.jpg)

### Data Overview
![Data Overview](screenshots/Data%20Overview.jpg)

### Energy by Property Type
![Energy by Property Type](screenshots/Energy%20by%20Property%20Type.jpg)

### Energy by Construction Age
![Energy by Construction Age](screenshots/Energy%20by%20Construction%20Age.jpg)

### Energy by Built Form
![Energy by Built Form](screenshots/Energy%20by%20Built%20Form.jpg)

### Energy by Fuel Type
![Energy by Fuel Type](screenshots/Energy%20by%20Fuel%20Type.jpg)

### Key Insights & Recommendations
![Key Insights](screenshots/Key%20Insights%20%26%20Recommendations.jpg)

---

## Data Source

- **Source:** UK Government EPC Register
- **URL:** https://epc.opendatacommunities.org/
- **License:** Open Government Licence v3.0

---

## Contact

**Mambiyea Kapee**  
[LinkedIn Profile](https://www.linkedin.com/in/mambiyea-kapee)
