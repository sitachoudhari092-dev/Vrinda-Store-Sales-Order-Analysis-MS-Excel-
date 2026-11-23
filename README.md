# Vrinda-Store-Sales-Order-Analysis-MS-Excel-
An Excel workbook (`Vrinda store data.xlsx`) built around the **Vrinda Store** sales dataset (**31,047 rows** across **21 columns** in `INR`), paired with summary/pivot sheets analyzing order volume, sales amount, customer demographics, channels, order statuses, and top states.



## Dataset Summary (`Vrinda Store`)
- **Total Records:** 31,047 rows (`28,471` unique `Order ID` values; `28,437` unique `Cust ID` values; `5,287` unique `SKU` values)
- **Total Order Amount:** INR 21,176,377 (Mean: INR 682.07 | Median: INR 646.00 | Min: INR 229 | Max: INR 3,036)
- **Total Quantity (`Qty`):** 31,237 units (mostly single-item orders: `Qty = 1` in 30,891 rows)
- **Coverage:** Indian shipping locations (`ship-country = IN` across 50 states/territories and 2,603 cities) across 12 months (`January`–`December`)

## Key Findings from the Dataset
- **Order Status Distribution:**
  - **Delivered:** 28,641 orders (92.25% of orders; INR 19,710,544)
  - **Returned:** 1,045 orders (3.37% of orders; INR 719,147)
  - **Cancelled:** 844 orders (2.72% of orders; INR 481,844)
  - **Refunded:** 517 orders (1.67% of orders; INR 264,842)
- **Customer Demographics:**
  - **Gender:** `Women` accounts for 21,553 orders (69.42%) and INR 13,562,773 (64.05%), while `Men` accounts for 9,494 orders (30.58%) and INR 7,613,604 (35.95%).
  - **Age Group:** `Adult` leads with 15,543 orders (50.06% / INR 10,608,757), followed by `Teenager` (9,415 orders / 30.32% / INR 6,412,858) and `Senior` (6,089 orders / 19.61% / INR 4,154,762).
- **Top Categories by Volume & Amount:**
  - `Set` (12,391 orders / INR 10,507,546), `kurta` (10,446 orders / INR 4,959,377), and `Western Dress` (4,066 orders / INR 3,148,836) make up the bulk of sales, followed by `Top`, `Saree`, `Ethnic Dress`, `Blouse`, and `Bottom`.
- **Top Sales Channels:**
  - `Amazon` (11,016 orders / INR 7,519,933), `Myntra` (7,254 orders / INR 4,941,540), and `Flipkart` (6,703 orders / INR 4,573,301) lead order volume and sales, alongside `Ajio`, `Nalli`, `Meesho`, and `Others`.
- **Top States in Main Dataset (`ship-state`):**
  - `MAHARASHTRA` (4,519 orders / INR 2,990,221), `KARNATAKA` (3,988 orders / INR 2,646,358), `UTTAR PRADESH` (2,882 orders / INR 2,104,659), `TELANGANA` (2,527 orders / INR 1,712,439), and `TAMIL NADU` (2,679 orders / INR 1,678,877).

## Workbook Structure
- `Vrinda Store`: Main 31,047-row transaction dataset.
- `order vs sales`: Summary table showing `April` (INR 392,572 across 480 orders).
- `Men vs Women`: Sales amount comparison (`Men`: INR 179,661 | `Women`: INR 212,911 in the filtered summary view).
- `order status`: Order count breakdown (`Delivered`: 454, `Cancelled`: 14, `Returned`: 11, `Refunded`: 1 in the filtered summary view).
- `Top 5 states`: Sales summary for `MAHARASHTRA`, `UTTAR PRADESH`, `KARNATAKA`, `DELHI`, and `TELANGANA` in the summary view.
- `Mens Vs women`: Age group (`Adult`, `Senior`, `Teenager`) by gender (`Men`, `Women`) summary table.
- `orders channel`: Channel summary view.
- `Vrinda store Report`: Report tab (currently blank in the workbook).

## Notes & Next Steps for Polishing
- Several summary tabs in the workbook currently reflect filtered/single-period slices (such as `April` / 480 orders), whereas `Vrinda Store` contains the full 31,047-row dataset—adding full-dataset Pivot Tables and completing `Vrinda store Report` are great next improvements.
