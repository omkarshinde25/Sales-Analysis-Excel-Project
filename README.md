# Sales-Analysis-Excel-Project

This repository contains analysis built from **`Excel Project 2.xlsx`**.  
It includes cleaned datasets, formulas/pivots, and (optionally) charts or dashboards created in Microsoft Excel.

Tip: Replace placeholder sections (TODO) with your actual project details before publishing to GitHub.


## Project Goals
- Clean and prepare raw data for analysis.
- Explore trends with pivot tables, formulas, and charts.
- Derive key metrics (KPIs) like totals, averages, growth %, etc.
- Build a simple dashboard for insights (optional).


## How to Use
1. Clone or download this repo.
2. Open **`Excel Project 2.xlsx`** in Excel (or LibreOffice/Google Sheets if compatible).
3. Explore the sheets listed below (Data Dictionary + Preview).
4. (Optional) Publish dashboard screenshots in the `assets/` folder and link them in this README.


## Repo Structure (suggested)
```
.
├── Excel Project 2.xlsx        # Main workbook
├── assets/                     # Screenshots of charts or dashboard (optional)
├── data/                       # Any exported CSVs (optional)
└── README.md                   # This file
```


## Sheets & Data Dictionary
### Sheet: DataAnalysis
| Column | Type |
|---|---|
| Sum of Total Selling Value | Text |
| Unnamed: 1 | Text |
| Unnamed: 2 | Decimal/Float |
| Unnamed: 3 | Text |
| Values | Text |
| Unnamed: 5 | Text |
| Unnamed: 6 | Decimal/Float |
| Unnamed: 7 | Text |
| True | Text |
| True.1 | Text |
| True.2 | Text |
| Unnamed: 11 | Decimal/Float |
| Unnamed: 12 | Text |
| Values.1 | Text |
| Unnamed: 14 | Text |
| Unnamed: 15 | Decimal/Float |
| Unnamed: 16 | Text |
| Unnamed: 17 | Text |
| Values.2 | Text |
| Unnamed: 19 | Text |
| Unnamed: 20 | Decimal/Float |
| Unnamed: 21 | Decimal/Float |
| Product41 | Text |
| Ft | Text |
| 22952.16 | Decimal/Float |
| 132 | Decimal/Float |
| Unnamed: 26 | Decimal/Float |
| 60 | Text |
| 35 | Decimal/Float |
| 35.1 | Decimal/Float |

Preview (first 5 rows): [Download CSV](sandbox:/mnt/data/preview_DataAnalysis.csv)

### Sheet: Dashboard
No preview available for this sheet (empty or unreadable).

### Sheet: Input Data
| Column | Type |
|---|---|
| DATE | Date/Time |
| PRODUCT ID | Text |
| QUANTITY | Integer |
| SALE TYPE | Text |
| PAYMENT MODE | Text |
| DISCOUNT % | Integer |
| PRODUCT | Text |
| CATEGORY | Text |
| UOM | Text |
| BUYING PRIZE | Integer |
| SELLING PRICE | Decimal/Float |
| Total Buying Value | Integer |
| Total Selling Value | Decimal/Float |
| Day | Integer |
| Month | Text |
| Year | Integer |

Preview (first 5 rows): [Download CSV](sandbox:/mnt/data/preview_Input_Data.csv)

### Sheet: Master Data
| Column | Type |
|---|---|
| PRODUCT ID | Text |
| PRODUCT | Text |
| CATEGORY | Text |
| UOM | Text |
| BUYING PRIZE | Integer |
| SELLING PRICE | Decimal/Float |

Preview (first 5 rows): [Download CSV](sandbox:/mnt/data/preview_Master_Data.csv)


## Analysis Notes (TODO)
- Key KPIs: e.g., Total Sales, Average Ticket Size, Conversion Rate, Month-over-Month Growth.
- Top Insights: e.g., Best-performing product/category/region; peak months; outliers.
- Methods Used: Pivot Tables, VLOOKUP/XLOOKUP, INDEX-MATCH, SUMIFS, COUNTIFS, Power Query, Slicers, Conditional Formatting.


## Dashboard / Charts (TODO)
Add screenshots here (store images in `assets/` and reference like this):

```
![Dashboard Overview](assets/dashboard_overview.png)
```


## Reproducibility (TODO)
- Steps to rebuild the analysis from raw data (if applicable).
- Any assumptions or data cleaning rules (e.g., date formats, missing values handling).
- Version Info: Excel version, add-ins used (Power Query/Power Pivot).


## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request for improvements or bug fixes.


## License
This project is licensed under the MIT License. See the `LICENSE` file (or update this section if you prefer another license).
