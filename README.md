# sales-analysis

Analysis of AAL (Australian Apparel) sales in Q4 2020, state by state, to guide expansion and design sales programs for low-revenue states. Course-end project for *Applied Data Science with Python*.

## Structure
```
data/AusApparalSales4thQrt2020.csv   raw data: 7,560 rows, 1 Oct to 30 Dec 2020
notebooks/sales_analysis.ipynb       full report: wrangling, analysis, dashboard, recommendations
reports/sales_analysis.html          the executed notebook exported to HTML (opens in any browser)
```

## Run
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter lab notebooks/sales_analysis.ipynb
```

## Headline results
| | |
|---|---|
| Q4 revenue | AUD 340.3M (136,121 units at a flat AUD 2,500 per unit) |
| Top states | VIC 31%, NSW 22% (together 53%) |
| Bottom states | WA, NT, TAS (about 6.5% each). VIC sells 4.8× what WA does |
| Groups | balanced at about 25% each (Men highest, Seniors lowest, 2% spread, not significant) |
| Time of day | Morning is the narrow peak, Evening is off-peak |
| Seasonality | Nov down 21% from Oct, Dec up 49% from Nov |
