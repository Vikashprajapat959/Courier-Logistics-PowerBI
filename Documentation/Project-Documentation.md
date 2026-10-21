\# LOGISENSE AI — Project Documentation



\## 1. Project Overview



LOGISENSE AI is a logistics performance analytics project built using Microsoft Power BI. It helps users explore courier delivery operations through interactive visualizations, key performance indicators (KPIs), and category-based comparisons.



The project focuses on understanding delivery delays, delivery costs, distance, delivery partner ratings, vehicle types, weather conditions, and delivery modes.



\## 2. Problem Statement



Courier and logistics operations generate data across multiple delivery attributes. Reviewing these records manually can make it difficult to identify patterns and compare performance.



This project organizes delivery data into an interactive dashboard so users can explore operational metrics, investigate delay patterns, and identify areas that may deserve further analysis.



\## 3. Project Objectives



\- Summarize overall delivery performance.

\- Measure delayed deliveries and the delay rate.

\- Compare delay patterns across vehicle types and weather conditions.

\- Explore delivery partner ratings and delivery modes.

\- Examine average delivery cost and distance.

\- Present the analysis through clear and interactive Power BI reports.



\## 4. Technology Stack



| Technology | Purpose |

|---|---|

| Microsoft Power BI Desktop | Dashboard creation and reporting |

| CSV | Delivery dataset |

| Power Query | Data loading and transformation |

| DAX | KPI and measure calculations |

| Git and GitHub | Version control and project sharing |



\## 5. Dataset Overview



\*\*Dataset file:\*\* `Dataset/Raw\_Data/Delivery\_Logistics.csv`



The dataset includes fields related to:



\- Delivery identifiers and delivery status

\- Delay indicators

\- Delivery cost and delivery ratings

\- Delivery time and expected delivery time

\- Distance and package weight

\- Delivery mode and delivery partner

\- Vehicle type, region, and weather condition

\- Package type



The analysis depends on the quality, completeness, and definitions of the source dataset.



\## 6. Key Performance Indicators



\### Total Deliveries



Counts the number of records in the delivery dataset.



\### Delayed Deliveries



Counts records where the `delayed` field is marked `yes`.



\### Delay Rate



Calculates the proportion of delayed deliveries among all delivery records.



\*\*Formula:\*\*



`Delay Rate = Delayed Deliveries / Total Deliveries`



The measure is formatted as a percentage in Power BI.



\### Average Delivery Cost



Calculates the average value of the `delivery\_cost` field.



\### Average Distance



Calculates the average value of the `distance\_km` field.



\## 7. Dashboard Pages



\### Page 1 — Executive Overview



Provides a high-level summary of logistics performance using KPI cards and charts. It covers delivery delays, vehicle-wise comparisons, weather-related patterns, partner ratings, and expected versus actual delivery time.



Available slicers include region, vehicle type, and weather condition.



\### Page 2 — Delay Intelligence



Provides a more focused view of delay-related patterns. Its visualizations explore vehicle types, weather conditions, delivery partners, delivery modes, delivery status, cost, distance, and delivery time.



\## 8. Analysis Methodology



1\. Load the CSV dataset into Power BI Desktop.

2\. Review column names and data types.

3\. Check missing values and inconsistent categories.

4\. Create DAX measures for the required KPIs.

5\. Build charts and KPI cards around relevant delivery attributes.

6\. Add slicers to enable interactive filtering.

7\. Compare patterns across categories and validate results against the underlying data.



\## 9. Limitations



\- The dashboard is based on the included dataset and is not necessarily connected to live logistics systems.

\- Observed relationships do not establish that weather, vehicle type, or another attribute causes delivery delays.

\- The quality of the results depends on the source data and measure definitions.

\- No validated predictive AI model is claimed as part of this Power BI report.

\- Final findings and recommendations should be added only after checking the actual dashboard results.



\## 10. Future Scope



\- Add a documented data dictionary and verified dataset attribution.

\- Include validated findings and actionable logistics recommendations.

\- Improve report navigation and visual consistency.

\- Test refresh and data-source paths from a fresh repository download.

\- Explore forecasting or predictive analytics as a separate, validated future enhancement.



\## 11. How to Open the Project



1\. Open `PowerBI/Courier\_Logistics.pbix` in Microsoft Power BI Desktop.

2\. If prompted, locate `Dataset/Raw\_Data/Delivery\_Logistics.csv`.

3\. Refresh the data and resolve any source-path issues.

4\. Review KPI values, charts, and slicer interactions.



\## 12. Author



\*\*Vikash Prajapat\*\*



\*\*Project:\*\* LOGISENSE AI — Logistics Intelligence \& Delivery Optimization System



\---



\*Documentation for an interactive Power BI logistics analytics project.\*



