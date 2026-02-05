# Hotel Performance Dashboard (Power BI)

This Power BI report analyzes hotel performance across multiple properties and cities, focusing on revenue, pricing, occupancy, and booking behavior.  
The dashboard provides a quick operational and management-level overview.

---

## What this dashboard shows

- Revenue, RevPAR, ADR, and Occupancy
- Realisation, cancellation, and no-show rates
- Weekly performance trends
- Booking performance by platform and room category
- Property-level comparison

Week-over-week changes are highlighted for key metrics.

---

## Interactivity

The report supports interactive filtering by:

- City
- Room type
- Date (month / week)
- Booking platform

---

## Data model

The solution is built using a **star schema**:

- **Fact tables**: `fact_bookings`, `fact_aggregated_bookings`
- **Dimension tables**: `dim_hotels`, `dim_rooms`, `dim_date`

All calculations are implemented as **DAX measures**.

---

## Dashboard preview
![Dashboard Preview](/screenshot.png)


---

## Tools used

- Power BI Desktop
- DAX
- Power Query
