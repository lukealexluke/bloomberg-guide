# FA - Financial Analysis

`FA <GO>` provides comprehensive financial information for a company including historicla financials and consensus estimates.

[Insert Picture Here]

## Use `FA` For

- Pulling historical financial statements quickly
- Comparing adjusted vs. as-reported financials
- Reviewing profitability, leverage, liquidity, and growth ratios.
- Analyzing business or geographic segment performance.
- Exporting clean historical financials into Excel for DCF, comps, or credit analysis.
- Checking Bloomberg’s standardized definitions before using a field in a model.

## FA Workflow

[Insert Picture Here]

1. Load the company ticker and enter `FA <GO>`
2. Set the periodicity, currency, and number of periods.
3. Review Key Stats for a high-level snapshot.
4. Check the Income Statement, Balance Sheet, and Cash Flow tabs.
5. Use Ratios to review margins, ROIC, leverage, liquidity, and working capital.
6. Use Segments to understand revenue/profit drivers by business or geography.
7. Use Field Descriptions to verify definitions.
8. Export to Excel for modeling or further analysis.

## Toolbar Options

- Actions: View line-item descriptions and change the way data is displayed.
    - Show Chart Grid: Display financial data as a series of bar/line charts.
    - Set as Default Template: Set current view as default template
    - Fields
        - Search: Search for the location of specified line items.
        - View Description: View descriptions for each field currently displayed on screen.
    - Template
        - Customize: Add or remove fields from view.
- Export: Export currently selected template or report as a PDF or Excel workbook.
- Settings: Settings for templates and report
    - Fundamentals
        - Periodicity: Adjust the number of periods included and the periodicity.
        - Fundamentals: Change which filings status is preferred, or whether to use standardized vs. actual reportings.
    - Data
        - Growth/Average: Select whether to include growth rows.
        - Data: Select whether to include estimates, current/LTM data. Also choose whether to use common size values for each row, and percent of total rows for segment analysis.
    - Display: Change display settings for fields
    - Report/Excel: Change export settings.

## Tabs

Each tab contains different kinds of financial information under different fields, and offers different displays for each set of items.

### Key Stats

A set of templates that show key financial analysis statistics.

- BBG Adjusted Highlights (FA HLTS \<GO\>) - Data is adjusted to remoe the impact of abnormal items (as defined by Bloomberg).
- BBG GAAP Highlights (FA GAAP \<GO\>) - GAAP Highlights template. Data has been standardized for consistent accounting treatment and presentation across companies.
- Company Model (FA MODL \<GO\>) - Displays company-specific financial highlights, such as product costs and revenues.
- Earnings (FA ERN \<GO\>) - Displays earnings template.
- Enterprise Value (FA EV \<GO\>) - Displays enterprise value template.
- EV Ex Operating Leases (FA EVEXOL \<GO\>) - Displays enterprise value excluding operating leases template.
- Multiples (FA PRA \<GO\>) - Displays multiples template.
- Per Share (FA PSH \<GO\>) - Displays per share template.
- Stock Value (FA HSV \<GO\>) - Displays stock value template.

[Insert Picture Here]

### Income Statement (I/S)

This section is a stub currently.

### Balance Sheet (B/S)

This section is a stub currently.

### Cash Flow Statement (C/F)

This section is a stub currently.

### Ratios

- Profitability: Margins, ROIC, ROA.
- Growth: One-to-five-year annualized basis of trends.
- Credit: Analysis to see how leveraged a company is (D/E).
- Credit Ex Operating Leases: Pro-forma data for credit analysis excluding the impact of operating leases.
- Liquidity: Measures of the company’s short-term liquidity and solvency.
- Working Capital: Accounts receivable metrics, including cash conversion cycle analysis.
- Yield Analysis: Cash yields measured across the equity and firm levels.
- DuPont Analysis: Decomposition of ROE into its drivers.

[Insert Picture Here]

### Segments

- Segments
    - Business: Analyze a company's reported business segments with key metrics across different units, products, brands, or end markets.
    - Location: Look into the company's reported location segments for regional/national performance.
- Group By
    - Measure: Organize data by measures with all relevant segment data below each measure
    - Segments: Organize data by segment with all relevant measures below each segment
- View
    - Table: View data in tabular form
    - Chart: View data as a sankey chart.

### Addl

This section is a stub currently.

### ESG

This section is a stub currently.

### Custom

This section is a stub currently.

### Shared

This section is a stub currently.

## Important Notes

- Do not assume Bloomberg’s adjusted data matches the company’s reported numbers. You may want to use As-Reported for exact dollar amounts.
- Always check whether the data is annual, quarterly, LTM, or estimated.
- Confirm the currency before comparing companies.
- Be careful comparing companies with different fiscal year-ends.
- Segment reporting may change over time, making historical comparisons harder.
- Exported data should be reviewed before being used in a model.


#### Adjusted vs. As-Reported Data

- As-Reported Data: Reflects the company’s original filing presentation.
- Adjusted Data: Reflects Bloomberg’s standardized adjustments, which may remove or reclassify certain items.
- For valuation work, always confirm which version you are using before exporting data.
- If a number looks unusual, use field descriptions or filings to verify Bloomberg’s treatment.

#### Related Functions

- [SPLC - Supply Chain Analysis](supply-chain-analysis.md)
- [DSCO - Company Documents & Search](company-documents-and-search.md)

