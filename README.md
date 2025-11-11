# Sector-Volatility-Analysis-PowerBI

# Sector Volatility Comparison Dashboard (2015–2025)
**Tech (XLK)** vs **Healthcare (XLV)** | Built in Power BI | Data via Yahoo Finance

<img width="1273" height="714" alt="image" src="https://github.com/user-attachments/assets/d6a4a055-9faf-4bc7-8384-ba94ffc168db" />

---

## Overview
This dashboard compares **sector-level volatility** between the **Technology** and **Healthcare** sectors over a 10-year period (2015–2025). It visualizes volatility trends, gaps, and performance correlations to help understand **market stability and risk behavior** between these two key sectors.

---

## Tools & Technologies
- **Python (yfinance, pandas)** – for data extraction and preprocessing  
- **Power BI** – for dashboard design and visualization  
- **Yahoo Finance API** – for sector ETF data (XLK, XLV)

---

## Dataset Description
The dataset contains **daily adjusted close prices** and derived metrics:
| Column | Description |
|---------|--------------|
| Date | Trading date |
| XLK | Adjusted close of Tech sector ETF |
| XLV | Adjusted close of Healthcare sector ETF |
| Daily Return | Percentage change in price |
| Volatility | Rolling standard deviation of returns |
| Sector | Tech / Healthcare |

Null values (non-trading days) are removed before analysis.

---

## Dashboard Insights
- **Tech sector (XLK)** shows higher volatility (avg 0.21%) compared to Healthcare (avg 0.15%)  
- **Volatility gap** averaged around 0.06, peaking during 2020 (COVID market shock)  
- **Returns trend** visualization reveals Tech’s faster rebound post-2021  

---

## Dashboard Features
| Visual | Description |
|---------|--------------|
| **Cards** | Show average volatility and volatility gap |
| **Line Chart** | Sector daily returns trend |
| **Area Chart** | Volatility comparison between sectors |
| **Table** | Monthly volatility with conditional formatting (🔴 negative, 🟢 positive) |
| **Slicer** | Year & Quarter filter for time-based analysis |

---

## Project Structure
sector-volatility-analysis-powerbi/  
├── sector_volatility_data.csv  
├── volatility_calculation.ipynb  
├── SectorVolatilityDashboard.pbix  
├── dashboard_preview.png  
└── README.md  


---

## How to Run
1. **Open Power BI Desktop**
2. Load `SectorVolatilityDashboard.pbix`
3. Ensure dataset file path is correct or refresh data connection
4. Interact with filters and visuals to explore volatility trends

---

## Future Enhancements
- Add correlation analysis between volatility & returns  
- Include more sectors (Energy, Finance, etc.)  
- Automate monthly updates using Power BI Service  

---

## **<u>Author</u>**

**Akshita Sharma**  
*Data Analyst | Power BI | Python | Excel | Visualization*  
