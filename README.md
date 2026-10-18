# Delivery KPI Dashboard (Tableau)

A Tableau story that tracks two operational KPIs for a parcel-delivery network across ten countries over six
weeks (weeks 41–46), and checks each country against its budget target.

## KPIs

| KPI | Definition | Target |
|---|---|---|
| **Outbound performance** | Weekly outbound performance rate, with parcel volume | At or above the country's budget |
| **Complaints quota** | Complaints per 10,000 parcels | At or below the country's budget |

Countries: Costa Rica, Colombia, Morocco, South Africa, Angola, Tunisia, India, Kenya, Japan and Argentina.

## What the analysis covers

For each KPI, overall and per week:

- minimum, maximum and aggregated value per country
- best and worst week by performance and by volume
- whether the target was met, and the deviation from target in points and in parcels or complaints

## Dashboard

The workbook is a Tableau story with four points:

1. Outbound KPI: all countries
2. Outbound KPI: Morocco
3. Complaints KPI: all countries
4. Complaints KPI: Morocco

## Repository contents

```
├── kpi_dashboard.twb   # Tableau workbook (story + worksheets)
└── KPI data.xlsx       # Weekly KPI data and the derived metrics
```

## Opening the workbook

Open `kpi_dashboard.twb` in Tableau Desktop or the free Tableau Public app. If Tableau asks for the data source,
point it to `KPI data.xlsx` in the same folder.

## License

[MIT](LICENSE)
