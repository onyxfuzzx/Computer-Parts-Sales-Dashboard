---
# Excel Computer Parts Sales Dashboard Analysis

This repository contains analysis of sales data from multiple regions and sellers, with visualizations and insights.

## Contents

- Sales data by region (east, north, south, west)
- Seller performance metrics
- Raw transaction data
- Calculated metrics and percentages

## Data Overview

The Excel file contains 4 sheets:
1. **DASHBOARD**: Interactive + Simple
2. **Sheet5**: Regional sales distribution with calculated percentages
3. **Sheet8**: Sales by seller with grand total
4. **Data**: Raw transaction data with seller, region, item, and sale amount

## Dashboard Overview
![image](https://github.com/user-attachments/assets/fcce4c83-d7f6-4986-a96b-611cfea1be18)


## Sheet Descriptions

### Sheet5: Regional Sales
- Shows percentage distribution of sales across 4 regions
- Contains formulas calculating:
  - Direct percentage (=B2, =B3, etc.)
  - Complement percentage (=1-C2, etc.)
  - Sum verification (=SUM(C2,D2), etc.)

### Sheet8: Seller Performance
- Lists 7 sellers with their normalized sales contributions
- Includes Grand Total that sums to 1 (normalized)

### Data Sheet
- Contains 100+ rows of transactional data with:
  - Seller names (8 unique sellers)
  - Regions (east, north, south, west)
  - Items sold (Mouse, Keyboard, Printer, etc.)
  - Sale amounts (from 100 to 1000)
  
## Formulas Used

- Percentage calculations: `=B2`, `=B3`, etc.
- Complement calculations: `=1-C2`, etc.
- Verification sums: `=SUM(C2,D2)`, etc.

## Usage

1. Clone this repository
2. Open the Excel file in `data/DASHBOARD.xlsx`

## Key Insights

- Total sales are normalized to 1 across all regions
- East region accounts for ~28.4% of sales
- Pc Zone is the top seller with ~16.3% of total sales
- Monitor sales appear to be significant outliers in the data

## Requirements

- Microsoft Excel or compatible spreadsheet software
---
