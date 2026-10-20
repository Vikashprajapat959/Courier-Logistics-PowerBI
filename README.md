# Courier Logistics Performance Analytics

An interactive **courier and logistics analytics dashboard built with Microsoft Power BI**. The project organizes delivery data into a report for exploring delivery volume, delays, delivery cost, distance, partner ratings, and potential relationships between delivery performance and weather or vehicle type.

> **Project status:** Dashboard and dataset files are included in this repository. The report is still being validated and improved; results should be checked against the source data before being used for operational decisions.

## Project at a glance

- **Tool:** Microsoft Power BI Desktop
- **Dataset:** `Dataset/Raw_Data/Delivery_Logistics.csv`
- **Power BI report:** `PowerBI/Courier_Logistics.pbix`
- **Repository branch:** `dev`

## What the dashboard covers

The report is designed to help users explore:

- **Delivery KPIs:** total deliveries, delayed deliveries, delay rate, average delivery cost, and average distance.
- **Delay analysis:** compare delivery delay patterns across the available categories.
- **Partner performance:** explore delivery partner ratings in the report.
- **Weather impact:** inspect delivery performance by weather condition.
- **Vehicle comparison:** explore performance by vehicle type.
- **Interactive filtering:** use the available Region, Vehicle Type, and Weather Condition slicers to narrow the report.

The exact values shown in the report depend on the loaded data and the filters selected. Verify measures and filter behaviour in Power BI before presenting any figures as final findings.

## Repository structure

```text
Courier-Logistics-PowerBI/
├── Dataset/
│   └── Raw_Data/
│       └── Delivery_Logistics.csv
├── Documentation/
├── PowerBI/
│   └── Courier_Logistics.pbix
├── Screenshots/
└── README.md
```

## Open the report

1. Download or clone this repository.
2. Open `PowerBI/Courier_Logistics.pbix` using **Power BI Desktop**.
3. If Power BI asks for the CSV source location, point it to `Dataset/Raw_Data/Delivery_Logistics.csv` and apply the changes.
4. Check the slicers and visuals, then confirm that the KPI measures match the underlying dataset.

## Data and interpretation notes

- The CSV included in this repository is the report's data file. Add the original dataset source and any applicable licence or attribution here once confirmed.
- Treat dashboard patterns as descriptive analysis, not proof that a factor causes delivery delays.
- No predictive model or live logistics integration is documented in this repository. Do not interpret the dashboard as a real-time monitoring or AI prediction system.
- Before sharing final conclusions, validate data types, missing values, measure definitions, totals, and slicer interactions.

## Planned improvements

- Add dashboard screenshots to the `Screenshots/` folder.
- Document the data source, data dictionary, and key DAX measures in `Documentation/`.
- Record verified findings and practical recommendations based on the actual dataset.
- Test the report from a fresh download so its data connection works reliably.

## Author

**Vikash Prajapat**

---

Built as a Power BI analytics project focused on exploring courier delivery performance and communicating data-backed findings.
