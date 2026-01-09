Hotel Performance Dashboard (Power BI)
Overview

Power BI dashboard for analyzing hotel revenue, occupancy, and booking performance across multiple properties and cities.
The report focuses on key hospitality KPIs and weekly trends.

Key Metrics

Revenue

RevPAR

ADR

Occupancy %

Realisation %

DSRN / DBRN / DURN

Cancellation %

Average Rating

Includes week-over-week (WoW) change indicators.

Filters

City

Room type

Date (month / week)

Booking platform

Data Model

Star schema with:

Fact tables: fact_bookings, fact_aggregated_bookings

Dimension tables: dim_hotels, dim_rooms, dim_date

Business logic implemented using DAX measures.

Dashboard Preview

Tools

Power BI Desktop

DAX

Power Query
