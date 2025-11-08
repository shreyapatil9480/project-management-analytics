# Project Management Analytics

What basket characteristics predict high margin?

**Stakeholder:** Retail Analytics Manager

## Key Insights

- Promo baskets under 3 items rarely achieve high margin.
- Large-format stores show 14% higher high-margin conversion.
- Basket size above 8 items lifts margin odds even without promos.

## Dataset

Primary file: `data/retail_baskets.csv`  
Target variable: `high_margin`

## Getting Started

```bash
pip install -r requirements.txt
jupyter notebook notebooks/01_exploration.ipynb
```


## Next Steps

**Done.** Weekly stakeholder report automation is implemented — see ### Implemented below.

---
*Analytics portfolio project — 2025-08*

<!-- build 6 -->

### Implemented

```bash
pip install -r requirements.txt
python scripts/weekly_report.py
```
### Report output

After running `python scripts/weekly_report.py`, open `reports/weekly_summary.html` for the stakeholder summary.

